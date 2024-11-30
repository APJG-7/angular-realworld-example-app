pipeline {
  agent none
  stages {
    stage('front end') {
      agent {
        docker { image 'node:16-alpine' }
      }
      steps {
        sh 'node --version'
      }
      steps {
        sh 'npm run test'
      }
    }
  }
}
