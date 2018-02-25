pipeline {
    agent { docker 'python:3.5.1' }
    stages {
        stage('build') {
            steps {
                sh 'date'
                sh 'echo "Checking Python version: "'
                sh 'python --version'
                sh 'if [ $? == 0 ]; then echo "Version Check OK"; fi'
            }
        }
    }
}
