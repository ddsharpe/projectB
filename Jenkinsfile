pipeline {
    agent any

    environment {
        MESSAGE = getMessage()
    }
    stages {
        stage('build') {
            steps {
                sh 'echo ${MESSAGE}'
            }
        }
    }
}

def getMessage() {
    return "Hello World " + env.BRANCH_NAME
}