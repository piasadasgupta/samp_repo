pipeline
{
agent any

  stages
  {
    stage('Download_code')
    {
      steps
      {
      echo Checking-out
      }
    }
    
    stage('Deploy')
    {
      steps
      {
      echo Deploying
      ant -f ./build.xml deployUnpackaged
      }
    }
    
  }
}
