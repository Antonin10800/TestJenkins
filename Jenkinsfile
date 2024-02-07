/* Requires the Docker Pipeline plugin */
pipeline {
    agent none
    stages {
        stage('push') {
            agent any
            steps {
                sh "echo 'Multiple steps can be declared within a stage'"
            }
        }
    }
}
