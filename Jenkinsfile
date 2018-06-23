pipeline {
  agent any
  stages {
     stage('echo') {
       steps {
         sh 'echo \'jenkins test\''
       }
     }
   }
  environment {
    customWorkspace = 'master/'
  }
}
