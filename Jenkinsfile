pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://ketere: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@github.com/Ketere/ntn.git', branch: 'main', credentialsId: 'MyGithub')
      }
    }

  }
}