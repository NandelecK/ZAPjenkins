pipeline {
  agent {
    docker {
      image 'owasp/zap2docker-stable'
      args '-d -t -p 8090:8080 -host 0.0.0.0:2376'
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