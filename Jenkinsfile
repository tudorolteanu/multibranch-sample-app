pipeline{
  agent any
stages{
  stage('Hello'){
      steps{
          echo "Hello from fix-123 branch"
        }
    }
  
  stage('cat README'){
    when{branch "fix-*"}
    steps{  sh '''  cat README.md '''  }
  }
  
  
}
}
