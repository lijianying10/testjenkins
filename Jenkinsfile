pipeline {
  agent any
  stages {
    stage('Filter Condition 1') {
      parallel {
        stage('Filter Condition 1') {
          steps {
            echo '1'
          }
        }

        stage('Filter Condition 2') {
          steps {
            echo '2'
            sh '''echo kk
exit 1'''
          }
        }

      }
    }

    stage('Filter Condition 3') {
      steps {
        echo '3'
      }
    }

  }
}