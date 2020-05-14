pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        echo "Building"
      }
    }
    stage('Deploy'){
      steps{
        echo "This is Deploying stage"
      }
    }
    stage('Production'){
      steps{
        echo "This is prod"
        sh label: '', script: 'cat /opt/file.txt'
        
      }
    }
  }
}
