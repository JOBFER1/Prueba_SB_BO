pipeline {
  agent any
  stages {
    stage('Source') {
      steps {
        git 'https://github.com/JOBFER1/Prueba_SB_BO.git'
      }
    }

    stage('Build') {
      steps {
        tool 'MAVEN_3_8_6'
        bat 'mvn clean package'
      }
    }

  }
}