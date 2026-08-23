pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Run Python') {
            steps {
                bat 'python --version'
                bat 'python app.py'
            }
        }
    }
}
