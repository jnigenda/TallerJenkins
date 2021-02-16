pipeline {
  agent any
  stages {
    stage('Hola Mundo') {
      steps {
        echo 'Hola'
        bat(script: 'echo %PACH%', returnStdout: true)
      }
    }

    stage('Crear archivo') {
      steps {
        writeFile(file: 'archivo.txt', text: 'Prueba taller')
      }
    }

  }
}