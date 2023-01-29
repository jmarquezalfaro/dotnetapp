pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        ebCreateApplication 'appdotnet10'
      }
    }

  }
  environment {
    env = 'dotnet'
  }
}