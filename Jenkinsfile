pipeline {
  agent none
  stages {
    stage('Front End') {
      agent {
        docker { image 'node' }
        
      }
      steps {
        sh 'node --version'
      }
    }
  }
}
