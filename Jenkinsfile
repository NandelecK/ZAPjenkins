pipeline {
  agent any
  stages {
    stage('build') {
      agent {
        docker {
          image 'owasp/zap2docker'
          args '-d -p 8090:8090'
        }

      }
      steps {
        echo 'run owasp zap dock gg'
      }
    }
  }
}