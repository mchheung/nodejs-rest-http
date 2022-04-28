pipeline {
    agent { kubernetes { label 'nodejs-rest-http:latest' } }
    stages {
        stage('build') {
            steps {
                sh '/usr/bin/node --version'
            }
        }
    }
}
