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
        sh label: '', script: 'mkdir -p /opt/jenkins/'
        sh label: '', script: 'touch /opt/jenkins/genfile.txt'
        sh label: '', script: 'echo "This is Production stage" >>  /opt/jenkins/genfile.txt'
      }
    }
  }
}
