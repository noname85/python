pipeline {
    agent { docker 'python:3.5.1' }
    stages {
        stage('build') {
            steps {
                sh 'date'
                sh 'echo "Checking Python version: "'
                sh 'python --version'
                sh 'sleep 20'
            }
        }
        stage('deploy1') {
            steps {
                sh 'echo "Enter New new Deploy stage"'
            }
        }
    }
}
