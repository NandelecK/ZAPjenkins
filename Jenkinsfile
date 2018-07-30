pipeline {
  agent any
  stages {
    stage('build') {
      agent {
        docker {
          args '-d -p 8090:8090'
          image 'owasp/zap2docker-stable'
        }

      }
      steps {
        echo 'run owasp zap dock gg'
      }
    }
  }
}