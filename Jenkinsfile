pipeline {
  agent {
    docker {
      image 'owasp/zap2docker-stable'
      args '''-d -t -p 8090:8080 --name jenkinszap /bin/bash
'''
    }

  }
  stages {
    stage('build') {
      agent any
      steps {
        echo 'hello world ?'
      }
    }
  }
}