pipeline {
  agent any
  stages {
    stage('Analisis_Calidad_Codigo') {
      steps {
        build 'Analisis_Calidad_Codigo_Sonar'
      }
    }
    stage('Cargar_Analisis_Qamera') {
      steps {
        bat 'dir'
      }
    }
  }
}