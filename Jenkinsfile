pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        git 'https://github.com/dmatan45/MySoftware/click.py.git'
      }
    }

    stage('test') {
      steps {
        echo 'testind'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploying'
      }
    }

  }
}
