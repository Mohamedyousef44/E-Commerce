pipeline {
  agent any
  stages {
    stage('checkout code /git') {
      steps {
        git(url: 'https://github.com/AhmedHamada011/E-Commerce', branch: 'develop')
      }
    }

    stage('npm shelscript') {
      steps {
        sh 'cd src && touch package.json && npm i'
      }
    }

  }
}