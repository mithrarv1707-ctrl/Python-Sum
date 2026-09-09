pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/mithrarv1707-ctrl/Python-Sum.git'
            }
        }

        stage('Build') {
            steps {
                bat 'python app.py 10 20'
            }
        }
    }
}