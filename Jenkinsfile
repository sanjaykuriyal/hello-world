pipeline {
  agent any
  stages {
    stage('Unit Test') {
      steps {
        echo 'mvn clean test'
      }
    }
    stage('Deploy Standalone') {
      steps {
        echo 'mvn deploy -P standalone'
      }
    }
  }
}
