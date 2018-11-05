pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello world!!!"'
            }
        }
        stage('Hello env') {
            steps {
               echo "My branch is: ${env.BRANCH_NAME}"
            }
        }
    }
}
