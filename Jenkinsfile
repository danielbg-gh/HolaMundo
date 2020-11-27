pipeline {
  agent any
  stages {
    stage('Paso-1') {
      steps {
        sh 'gcc hola.c -o hola.bin'
      }
    }

    stage('Instalacion') {
      steps {
        sh 'gcc -v'
      }
    }

  }
}