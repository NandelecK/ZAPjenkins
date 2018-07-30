pipeline {
  agent {
    docker {
      image 'owasp/zap2docker-stable'
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