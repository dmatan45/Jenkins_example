pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        git 'https://github.com/dmatan45/MySoftware.git'
      }
    }

    stage('test') {
      steps {
        python 'click.py'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploying'
      }
    }

  }
}
