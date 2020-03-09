#!/usr/bin/env groovy
pipeline {
    agent {
        docker { image 'node:12-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
