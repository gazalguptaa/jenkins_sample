pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        echo 'running Tests'
        bat 'python test.py'
      }
    }
    stage('Testing'){
      steps{
        echo 'Building jar files...'
        
      }
    }
  }
}
