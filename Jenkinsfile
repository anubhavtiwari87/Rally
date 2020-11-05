pipeline
{
 agent any
 stages
 {
  stage ('Make HTTP Call')
  {
  steps {
          script
          {
           sh '''
           curl 'http://dummy.restapiexample.com/api/v1/employees'
           '''
          }
        }
  }
 }
}
