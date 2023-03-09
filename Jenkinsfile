
pipeline {
	agent any

     stages {
         stage('Building'){
             steps {
                 echo 'The code will be noww built into artifact'
             }
         }
        
         
         stage('Artifact Archiving'){
             steps {
                 echo 'Artifact will be uploaded to artfact repository'
             }
         }
     
     
         stage('Testing'){
             steps {
                 echo 'Artifact will be Tested'
             }
         }

         stage('Staging'){
             steps {
                 echo 'Artifact is staged on staging server'
             }
         }

         stage('Deploy'){
             steps {
                 echo 'Software will be deployed'
             }
         }
     
   }
}
