pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''mvn -v 
mvn clean install test'''
      }
    }
  }
}