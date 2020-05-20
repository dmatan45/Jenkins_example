pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        python '1.py'
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
