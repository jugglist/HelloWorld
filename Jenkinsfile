pipeline {
  
  agent any
  
  stages {
    stage('DevBuild') {
      steps {
        echo 'Building...'
        sh 'chmod +x HelloWorld.py'
        sh './HelloWorld.py'
      }
    }

  }
}
