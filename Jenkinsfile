pipeline {
  agent any

  stages {
    stage('docker') {
      steps { 
        script {
          app = docker.build("backend-new")
        }
      
    }
    stage('build') {
      steps {
        echo 'start building'
        sh'''
        docker images
        '''
      }
    }
  }
}
