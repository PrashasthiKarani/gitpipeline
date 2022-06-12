pipeline{
agent any
stages{
  stage("build")
  {
    steps
    {
    echo "building the pipeline"
    }
  }
  stage("test")
  {
    steps{
    echo"testing the peipeline"
    }
  }
  stage("deploy")
  {
    steps{
      echo"deloying the pipeline"
    }
 }
}
post {
    always {
      echo "This will always be executed"  
    }
    
  }
}
