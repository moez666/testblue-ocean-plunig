pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'bonjour papa'
      }
    }

    stage('test ') {
      parallel {
        stage('test ') {
          steps {
            echo 'bonjour papa'
          }
        }

        stage('test 1') {
          steps {
            echo 'bonjour papa 1'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'bonjour papa complet'
      }
    }

  }
}