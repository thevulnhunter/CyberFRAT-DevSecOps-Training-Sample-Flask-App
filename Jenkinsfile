pipline {
  agent any
  
  stages {
    stage('Build Docker Image') {
      steps {
        sh 'docker build -t cyberfrat:$BUILD_NUMBER .'
        }
      }
    }
  }
        
      
