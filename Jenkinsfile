pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                sh 'pip install -r requirements.txt'
            }
        }
        stage('Test') {
            steps {
                sh 'python -m pytest'
            }
        }
        stage('Deploy') {
            steps {
                // Add deployment steps here if needed
            }
        }
    }
}
