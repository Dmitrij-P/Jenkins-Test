pipeline {
  agent {
    docker {
      image 'jenkins/agent:alpine-jdk21'
    }
  }
  stages {
    stage('Install Python') {
      steps {
        sh 'apk add --no-cache python3 py3-pip'
        sh 'python3 --version'
      }
    }
  }
}
