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
           bat '''
           ping 'http://dummy.restapiexample.com/api/v1/employees'
           '''
          }
        }
  }
 }
}
