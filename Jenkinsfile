pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'empezamos BUILD'
        sh 'mvn clean install -Dlicense.skip=true'
        echo 'BUILD realizada correctamente'
      }
    }

  }
}