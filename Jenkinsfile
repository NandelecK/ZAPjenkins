pipeline {
  agent {
    docker {
      image 'owasp/zap2docker-stable'
      args '-d -p 3000:3000'
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