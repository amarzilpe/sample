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
        sh label: '', script: 'sudo mkdir -p /opt/jenkins'
        
      }
    }
  }
}
