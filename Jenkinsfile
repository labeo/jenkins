pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        writeFile(file: 'file', text: 'tekst')
        sh 'echo \'jenkins test\''
        echo 'pwd()'
      }
    }
  }
  environment {
    customWorkspace = 'master/'
  }
}