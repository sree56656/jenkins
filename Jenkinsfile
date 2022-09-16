pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                python3 'jenkins.py'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
