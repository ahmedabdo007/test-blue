pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hi from build'
      }
    }

    stage('test') {
      steps {
        echo 'hi from test stage '
      }
    }

    stage('deploy') {
      steps {
        input(message: 'you want to deploy , are you sure ?', id: 'yes')
      }
    }

  }
}