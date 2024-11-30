pipeline {
  agent none
  stages {
    stage('Front End') {
      agent {
        docker { image 'node' }
      }
      steps {
        sh 'node --version'
        sh 'npm install'
        sh 'npm run test'
      }
    }
  }
}
