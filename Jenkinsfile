pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        echo 'running Tests'
        bat 'mvn test'
      }
    }
    stage('Testing'){
      steps{
        echo 'Building jar files...'
        bat 'mvn package'
      }
    }
  }
}
