pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'First Jenikins Pipeline'
      }
    }

    stage('Unit Test') {
      steps {
        sh './mvnw test'
      }
    }

  }
}