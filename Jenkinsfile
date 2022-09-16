pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'python --version'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'python3 jenkins.py'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
