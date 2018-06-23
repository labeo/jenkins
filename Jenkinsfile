pipeline {
    agent {
        label {
            label ""
            customWorkspace "C:/work/${BRANCH_NAME}"
        }
    }
    stages {
        stage("foo") {
            steps {
                echo "Workspace dir is ${pwd()}"
            }
        }
    }
}
