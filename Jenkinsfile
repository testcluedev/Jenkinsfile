/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.11.4-r1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
