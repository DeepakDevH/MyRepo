pipeline {
  agent any
  stages {
    stage('Get Code from Git') {
      steps {
        git(url: 'https://github.com/DeepakDevH/MyRepo.git', branch: 'Deepak', poll: true)
      }
    }

  }
}