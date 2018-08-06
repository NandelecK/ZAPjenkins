pipeline {
  agent {
    docker {
      image 'owasp/zap2docker-stable'
      args '-d -t -p 8090:8080'
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