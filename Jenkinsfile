pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Welcome to Jenkins World'
                echo 'Hi'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}
