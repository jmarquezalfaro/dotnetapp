pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        ebCreateApplication 'appdotnet10'
      }
    }

    stage('Deploy') {
      steps {
        ebCreateEnvironment(applicationName: 'dotnetapp11', environmentName: 'dotnet')
      }
    }

  }
  environment {
    env = 'dotnet'
  }
}