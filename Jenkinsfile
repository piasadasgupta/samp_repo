pipeline
{
agent any

  stages
  {
    stage('Download_code')
    {
      steps
      {
      echo "Checking-out"
      }
    }
    
    stage('Deploy')
    {
      steps
      {
      echo "Deploying"
      bat 'ant -f ./build.xml deployUnpackaged'
      }
    } 
  }
}
