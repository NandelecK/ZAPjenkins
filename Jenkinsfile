pipeline {
  agent {
    docker {
      image 'owasp/zap2docker-stable'
      args '-d -p 8090:8090'
    }

  }
  stages {
    stage('build') {
      agent any
      steps {
        echo 'run owasp zap dock gg'
      }
    }
  }
}