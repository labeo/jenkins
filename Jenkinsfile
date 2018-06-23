pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        sh 'echo \'jenkins test\''
        writeFile(file: 'file', text: 'tekst')
      }
    }
  }
  environment {
    customWorkspace = 'master/'
  }
}