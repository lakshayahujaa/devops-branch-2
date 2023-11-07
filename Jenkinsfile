pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo "Building the project 2"'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Running tests 2"'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploying the project 2"'
            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded! 2'
        }
        failure {
            echo 'Pipeline failed! 2'
        }
    }
}
