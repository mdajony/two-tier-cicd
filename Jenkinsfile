pipeline {
  agent any

  stages {
    stage('build') {
      steps {
        echo 'start building'
        app = docker.build("backend-new")
        sh'''
        docker images
        '''
      }
    }
  }
}
