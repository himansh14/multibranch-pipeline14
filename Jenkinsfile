pipeline {
  agent {label 'slavenode'}
  options {
    buildDiscarder(logRotator(numToKeepStr: '5'))
  }
  stages {
    stage('Environment') {
      steps {
        echo "Hi this is my normal environment for working"
      }
    }
  }
}
