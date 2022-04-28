pipeline {
    agent { kubernetes { label 'nodejs-rest-http:latest' } }
    node('nodejs-rest-http') {
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
