pipeline {
    agent none
    stages {
        stage('build') {
            steps {
                sh 'date'
                sh 'echo "Checking Python version: "'
                sh 'python holaJenkins.py'
                sh 'hostname'
            }
        }
  
    }
}
