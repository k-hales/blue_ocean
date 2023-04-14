pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'testing'
          }
        }

        stage('parallel') {
          steps {
            echo 'testing'
          }
        }

      }
    }

    stage('build') {
      steps {
        echo 'building environmnet'
      }
    }

    stage('cleanup') {
      steps {
        echo 'cleaning environment'
      }
    }

  }
}