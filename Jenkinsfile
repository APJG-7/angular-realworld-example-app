pipeline {
  agent none
  stages {
    stage('Front End') {
      agent {
        docker { image 'node:latest' }
        
      }
      steps {
        sh 'node --version'
      }
    }
  }
}
