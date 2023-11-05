pipeline {
  agent any
  stages {
    stage('checkout code /git') {
      steps {
        git(url: 'https://github.com/AhmedHamada011/E-Commerce', branch: 'develop')
      }
    }

    stage('changelog ') {
      steps {
        sh 'cat ls -l > CHANGELOG.md'
      }
    }

  }
}