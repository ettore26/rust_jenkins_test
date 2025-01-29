/* Requires the Docker Pipeline plugin */
pipeline {
    // agent { docker { image 'golang:1.23.4-alpine3.21' } }
    // agent { docker { image 'rust:1.83.0-alpine3.21' } }
    agent any
    stages {
        stage('build') {
            steps {
                // sh 'go version'
                // sh 'rustc --version'
                echo 'Hello, World!'
            }
        }
    }
}

