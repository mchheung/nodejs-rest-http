pipeline {
    agent { kubernetes { label 'nodejs-rest-http:latest' } }
    node {
        checkout scm
        stages {
            stage('build') {
                steps {
                    sh '/usr/bin/node --version'
                }
            }
        }
    }
}
