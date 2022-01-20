pipeline {
  agent any
  stages {
    stage('checkout ANSWER3') {
      steps {
        sh 'git checkout answer3'
        echo 'hemos cambiado de rama con git checkout answer3'
      }
    }

    stage('Build') {
      steps {
        echo 'ahora probamos el BUILD'
        sh 'mvn clean install -Dlicense.skip=true'
        echo 'BUILD realizado'
      }
    }

  }
}