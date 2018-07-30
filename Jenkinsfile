pipeline {
  agent {
    docker {
      image 'owasp/zap2docker-stable'
      args '-u zap -p 8090:8090 -i owasp/zap2docker-stable zap.sh -daemon -host 0.0.0.0 -port 8090'
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