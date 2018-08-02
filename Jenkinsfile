pipeline {
  agent {
    docker {
      image 'owasp/zap2docker-stable'
      args '-d -t -p 8080:8090'
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