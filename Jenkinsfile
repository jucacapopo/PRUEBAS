pipeline {
  agent any
  stages {
    stage('inicio') {
      steps {
        echo 'HOLA DESDE STAGE INICIO'
        sh 'sh sudo apt-get update'
      }
    }
    stage('TEST2') {
      steps {
        echo 'HOLA DESDE SATAGE 2'
      }
    }
  }
}