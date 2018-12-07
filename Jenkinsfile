pipeline {

  agent { label 'master' }
 
  stages {

     stage ('check-out code') { 

         steps {
           
             cleanWs()
 
             git branch: 'grails3_migration', credentialsId: '64113721-dfcd-4ed4-89f5-8658ed598ada', url: 'https://bitbucket.org/tsmojo/cloud-environment-simulator/src/grails3_migration/'
      
         }

         }

     stage ('build') {

          steps {
  
             dir('C:\\Program Files (x86)\\Jenkins\\workspace\\CES-BUILD-JOB\\CES-Source') {

                
 
             }

          }

     }

  }

}
