pipeline {
  agent any
  
  checkout scm
  stage("Build") {
    sh "npm install"
  }
  stage("Deploy") {
    sh "npm run openshift"
  }
}
