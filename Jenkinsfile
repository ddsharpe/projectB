pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                message = getMessage()
                sh 'echo ${message}'
            }
        }
    }
}

def getMessage() {
    return "Hello World " + env.BRANCH_NAME
}