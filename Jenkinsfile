pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/alexj01/k8s-poc', branch: 'develop', poll: true)
      }
    }
  }
}