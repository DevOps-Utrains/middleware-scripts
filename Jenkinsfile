pipeline {
    agent any

  stages{
      stage("create zip file"){
        steps {
          
         sh'zip middlewasreScript${BUILD_NUMBER}.zip *  --exclude Jenkinsfile'
          
        }
      stage("build"){
         steps {
          
         echo "build"
          
        } 
      }          
    }
}