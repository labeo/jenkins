pipeline {
  agent {
    node {
      customWorkspace "jenkins/${BRANCH_NAME}/"
      label ''
    }

  }
  stages {
    stage('start') {
      steps {
        echo "Workspace directory is ${pwd()}"
      }
    }
  }
}
