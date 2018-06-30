pipeline {
  agent {
    node {
      customWorkspace "jenkins/${BRANCH_NAME}/"
      label 'aa'
    }

  }
  stages {
    stage('start') {
      steps {
        echo "Workspace directory is ${pwd()}"
      }
    }
    stage('build') {
      steps {
        build 'job'
        sh 'dotnet restore'
      }
    }
  }
}
