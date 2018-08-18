pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        junit(allowEmptyResults: true, keepLongStdio: true, testResults: 'testng.xml')
      }
    }
  }
}