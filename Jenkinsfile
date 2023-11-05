pipeline {
  agent any
  stages {
    stage('checkout code /git') {
      parallel {
        stage('checkout code /git') {
          steps {
            git(url: 'https://github.com/AhmedHamada011/E-Commerce', branch: 'develop')
          }
        }

        stage('Change log') {
          steps {
            sh 'ls -l > CHANGELOG.md'
          }
        }

      }
    }

  }
}