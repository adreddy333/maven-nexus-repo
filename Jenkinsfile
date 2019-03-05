pipeline {
  agent {
    node {
      label 'install'
    }

  }
  stages {
    stage('compile') {
      steps {
        build 'build'
      }
    }
  }
}