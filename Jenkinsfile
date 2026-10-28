pipeline {
    agent { docker { image 'php:8.5.9-alpine3.24' } }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}