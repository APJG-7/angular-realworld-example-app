pipeline {
  agent none
  stages {
    stage('Front End') {
      agent {
        docker { image 'node:20.18.1-alpine3.20' }
        
      }
      steps {
        sh 'node --version'
        sh 'npm install'
        sh 'npm run test'
      }
    }
  }
}
