pipeline
{
  agent any
  stages
   {
     stage('clone the code/SCM Checkout')
      {
        steps
          {
            sh 'echo downloading code from github repo'
          }
      }
      
     stage('build the code')
      {
        steps
          {
            sh 'echo code is building'
          }
      }
     
     stage('deploy package to dev stage')
      {
        steps
          {
            sh 'echo deploying packages to dev env'
          }
      }
     
     stage('fucntional testing')
      {
        steps
          {
            sh 'echo fucntional testing is done'
          }
      }
      
     stage('Get Approval from QA manager')
      {
        steps
          {
            input "please approve for QA deplyment"
          }
      } 
      
     stage('Deploy to QA Env')
      {
        steps
          {
            sh 'echo deplying to QA env'
          }
      } 
     
   }
}
