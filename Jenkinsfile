pipeline {
  agent any
  stages {
    stage('Check Directory') {
      parallel {
        stage('Check Directory') {
          steps {
            sh '''echo "Check Directory >"
pwd'''
          }
        }

        stage('List All Available Files') {
          steps {
            sh '''echo "List All Files >"
ls -lha'''
          }
        }

        stage('Multi Branch') {
          steps {
            echo 'Hello'
          }
        }

      }
    }

    stage('Print Message') {
      steps {
        echo 'Next Stage In Pipeline'
      }
    }

  }
}