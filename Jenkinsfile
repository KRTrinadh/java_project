pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('stage1') {
      steps {
        node(label: 'master') {
          sshScript 'ls'
        }

      }
    }
  }
}