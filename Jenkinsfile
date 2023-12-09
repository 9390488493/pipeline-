pipeline {
  agent any
  stages {
    stage('dev') {
      parallel {
        stage('dev') {
          steps {
            echo 'dev stage'
          }
        }

        stage('test') {
          steps {
            echo 'testing stage'
          }
        }

        stage('ready') {
          steps {
            echo 'ready stage'
          }
        }

      }
    }

    stage('com') {
      steps {
        echo 'commit stage'
      }
    }

    stage('push') {
      steps {
        echo 'pushing stage'
      }
    }

    stage('deploy') {
      steps {
        echo 'deployment stage'
      }
    }

  }
}