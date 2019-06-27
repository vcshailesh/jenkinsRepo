pipeline {
  agent any
  stages {
    stage('git connect') {
      steps {
        git(url: 'https://github.com/vcshailesh/jenkinsRepo.git', branch: 'master', credentialsId: '3f00fb6a-67b5-4a0f-80a5-cdcd930f3a9c')
      }
    }
  }
}