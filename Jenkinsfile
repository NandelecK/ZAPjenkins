pipeline {
  agent {
    docker {
      image 'owasp/zap2docker-stable'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('initialize') {
      steps {
        echo 'run owasp zap dock'
      }
    }
  }
}