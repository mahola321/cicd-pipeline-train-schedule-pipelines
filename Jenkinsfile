pipeline  
{
stages any stages
  {
  stage ('build') 
        {
        echo 'Runnning build automation'
        sh './gradlew build -- no daemon
        archive Artifacts artifacts: 'dist/trainSchedule.zip'
        }
  }
}
