  pipeline {
  agent any
    stages {
      stage('Chekout GIT') {
        steps{
          echo 'Pulling...'
          git branch: 'main',
            url : 'https://github.com/daoud-habib/myPipeline.git'
            
        }
      }
     stage('Testing Maven')
      {steps {
        sh "mvn -verssion"
      }
      }
      
    }

    
  }
