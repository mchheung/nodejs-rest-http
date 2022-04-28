pipeline {
  agent any
  
  stages {
    stage("Build") {
      sh "npm install"
    }
    stage("Deploy") {
      sh "npm run openshift"
    }
  }
}
