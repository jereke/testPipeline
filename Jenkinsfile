pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build'
        sleep 10
      }
    }
    stage('test') {
      steps {
        input(message: 'seguir', id: 'seguir', ok: 'tira pa lante')
      }
    }
  }
}