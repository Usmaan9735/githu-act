pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'python test-practice/app.py'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Deployment successful!'
            }
        }
    }
}
