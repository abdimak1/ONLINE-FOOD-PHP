pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git(url: 'https://github.com/abdimak1/ONLINE-FOOD-PHP', branch: 'main')
      }
    }

    stage(' ') {
      steps {
        sh 'ls -la'
      }
    }

  }
}