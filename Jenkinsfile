pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                sh 'echo HELLO WORLD ' + ${env.BRANCH_NAME}
            }
        }
    }
}