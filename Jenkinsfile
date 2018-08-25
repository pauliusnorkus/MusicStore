pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        load '/scripts/s.groovy'
        input(message: 'Release to production', id: '555', ok: 'Ok-msg', submitter: 'Paulius', submitterParameter: 'PauliusID')
      }
    }
  }
}