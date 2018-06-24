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
        echo "Workspace dir is ${pwd()}"
      }
    }
  }
}
