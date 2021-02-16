pipeline {
  agent any
  stages {
    stage('Hola Mundo') {
      steps {
        echo 'Hola'
        bat(script: 'SET', returnStdout: true)
        bat 'echo %nombre%'
      }
    }

    stage('Crear archivo') {
      steps {
        writeFile(file: 'archivo.txt', text: 'Prueba taller')
      }
    }

  }
  environment {
    nombre = 'JESUS'
  }
}