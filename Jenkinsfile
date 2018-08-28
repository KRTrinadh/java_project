pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('stage1') {
      agent {
        node {
          label 'master'
        }

      }
      steps {
        echo 'Hello harish'
      }
    }
  }
}