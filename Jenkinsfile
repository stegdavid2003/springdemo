pipeline {
  agent any
  stages {
      stage('Checkout') {
          steps {
              script {
                  checkout scm
              }
          }
      }
      stage('Stage 1') {
          steps {
            script {
              echo 'Stage 1'
            }
          }
        }
      stage('Stage 2') {
          steps {
            script {
              echo 'Stage 2'
            }
          }
        }
    }
}