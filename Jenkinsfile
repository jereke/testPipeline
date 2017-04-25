pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build'
        sleep 10
      }
    }
    stage('test2') {
      steps {
        echo 'holaaaa'
        sleep 10
        input(message: 'tiro pa lante?', id: 'tirar', ok: 'si', submitter: 'admin')
      }
    }
  }
}