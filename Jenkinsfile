pipeline {
  agent {
    dockerfile {
      filename 'owasp/zap2docker-stable'
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