pipeline {
    agent {
        label {
            label ""
            customWorkspace "work/${BRANCH_NAME}/"
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
