pipeline {
  agent {
    docker {
      image 'owasp/zap2docker-stable'
      args 'run -d -p 8090:8090'
    }

  }
  stages {
    stage('build') {
      steps {
        echo 'run owasp zap dock gg'
      }
    }
  }
}