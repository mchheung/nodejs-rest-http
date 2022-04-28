pipeline {
    agent { docker { image 'nodejs-rest-http:latest' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
