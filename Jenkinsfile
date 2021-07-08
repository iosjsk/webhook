pipeline{
 agent any
 parameters{
  choice(name:'Branch',choices:'master','qa','development')
 }
    stages{
     stage('deploying build'){
       steps{
        git branch: '${Branch}', url: 'https://github.com/iosjsk/webhook.git'
         }
         }
     }    
   }      
