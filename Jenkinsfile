pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        def workspace = pwd()
        sh "echo ${workspace}"
      }
    }
  }
  environment {
    customWorkspace = 'master/'
  }
}
