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
        sh "sudo mkdir -p /opt/jenkins/jenfile.txt"
        sh "echo "This is Production stage" >>  /opt/jenkins/jenfile.txt"
      }
    }
  }
}
