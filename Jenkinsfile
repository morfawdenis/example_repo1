pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
        sh 'echo "Hello Our World"'
        sh 'ls -ltr'
      }
    }
  }
}
