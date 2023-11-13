pipeline {
  agent any
  stages {
    stage('Get terraform VM templates') {
      steps {
        git(url: 'https://github.com/Oyon84/ProxmoxConfigs', branch: 'main')
      }
    }

  }
}