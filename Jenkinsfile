pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'owasp/zap2docker-stable'
    }

  }
  stages {
    stage('build') {
      steps {
        echo 'run owasp zap dock'
      }
    }
  }
}