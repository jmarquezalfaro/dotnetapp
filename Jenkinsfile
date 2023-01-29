pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        ebCreateApplication 'app-jenkis'
      }
    }

  }
  environment {
    env = 'dotnet'
  }
}