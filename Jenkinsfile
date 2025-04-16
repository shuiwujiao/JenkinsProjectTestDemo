pipeline {
  agent {
    node {
      label 'test_node'
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
        sh '''ls
pwd'''
      }
    }

    stage('part2') {
      steps {
        sh '''ls
pwd'''
      }
    }

  }
}