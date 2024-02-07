Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'php:8.3.2-alpine3.19' } }
    stages {
        stage('build') {
            steps {
                set 'php --version'
                set 'Multiple steps can be declared within a stage'
            }
        }
    }
}