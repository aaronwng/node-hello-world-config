pipeline {
  agent {
    docker {
      image 'helloworld'
      args 'test'
    }

  }
  stages {
    stage('test') {
      steps {
        sh 'echo hello'
      }
    }
  }
}