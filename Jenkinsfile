pipeline {
  agent {
    docker {
      image 'owasp/zap2docker-stable'
      args '-d -p 8090:8090 -v /var/tmp:/var/tmp'
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