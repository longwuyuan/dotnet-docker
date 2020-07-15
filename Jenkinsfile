pipeline {
  agent {
    dockerfile {
      filename 'samples/aspnetapp/Dockerfile'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'cd samples/aspnetapp && docker build -t aspnetapp . '
      }
    }

  }
}