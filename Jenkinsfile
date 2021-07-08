pipeline{
 agent any
 parameters{
    choice(name: 'Branch',choices:['master','qa','development'],description:'select the branch')}
   stages{
     stage('deploying build'){
       steps{
         git branch: '${Branch}', url: 'https://github.com/iosjsk/webhook.git'
         }
         }
     }    
   }      
