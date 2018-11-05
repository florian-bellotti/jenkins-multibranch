pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello world!"'
            }
        }
        stage('Hello env') {
            steps {
                sh 'echo ${env.BRANCH_NAME}'
            }
        }
    }
}
