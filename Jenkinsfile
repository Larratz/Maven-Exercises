pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Comienza la instalación'
        sh '''mvn clean install -Dlicense.skip=true

'''
        echo 'Aqui queda hecho el BUILD'
      }
    }

  }
}