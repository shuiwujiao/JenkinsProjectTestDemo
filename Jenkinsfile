pipeline {
  agent {
    node {
      label 'node01'
    }

  }
  stages {
    stage('part1') {
      agent {
        node {
          label 'node01'
        }

      }
      steps {
        sh 'ls'
      }
    }

  }
}