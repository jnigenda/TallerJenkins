pipeline {
  agent any
  stages {
    stage('Hola Mundo') {
      steps {
        echo 'Hola'
      }
    }

    stage('Crear archivo') {
      steps {
        writeFile(file: 'archivo.txt', text: 'Prueba taller')
      }
    }

  }
}