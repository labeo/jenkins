pipeline {
  agent {
    node {
      customWorkspace "work/${BRANCH_NAME}/"
      label 'jenkins'
    }

  }
  stages {
    stage('start') {
      steps {
        echo "Workspace dir is ${pwd()}"
      }
    }
  }
}