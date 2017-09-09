pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        bat(script: 'echo "Hello World"', returnStatus: true, returnStdout: true)
      }
    }
  }
}