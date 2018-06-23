pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        step {
          def workspace = pwd()
          sh "echo ${workspace}"
        }
      }
    }
  }
  environment {
    customWorkspace = 'master/'
  }
}
