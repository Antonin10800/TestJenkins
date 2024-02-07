/* Requires the Docker Pipeline plugin */
pipeline {
    agent none
    stages {
        stage('push') {
            agent any
            steps {
                sh 'php --version'
                sh 'Multiple steps can be declared within a stage'
            }
        }
    }
}
