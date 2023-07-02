pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'first Jenkins pipeline'
        sh './mvnw clean compile'
      }
    }

    stage('Unit Test') {
      steps {
        sh '''./mvnw test
'''
      }
    }

  }
}