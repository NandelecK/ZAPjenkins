pipeline {
  agent {
    docker {
      image 'owasp/zap2docker-stable'
      args '-d -t '
    }

  }
  stages {
    stage('build') {
      agent any
      steps {
        echo 'hello worl ?'
      }
    }
  }
}