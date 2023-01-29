pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        awsebReleaser(credentialId: 'AKIA4ILGS6EI4RMKRAGJ', awsRegion: 'us-east-1', applicationName: 'app-jenkis', environmentId: 'Appjenkis-env', versionLabel: 'Sample Application	')
      }
    }

  }
  environment {
    env = 'dotnet'
  }
}