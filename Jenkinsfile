pipeline{
  agent{label "Jenkins"}
options{
  buildDiscarder logRotator(artifactDaysToKeepStr:'', artifactNumToKeepStr:'5', daysToKeepStr:'', numToKeepStr: '5')
  disableConcurrentBuilds()
}
stages{
  stage('Hello'){
      steps{
          echo "Hello from Jenkinsfile"
        }
    }
}
}
