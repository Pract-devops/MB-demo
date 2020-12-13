pipeline{
  agent any
  stages{
    stage("Maven Build"){
      steps{
        echo"building maven Project"
      }
    }
       stage("Deploy Dev"){
         when{
         branch 'dev'
         }
      steps{
        echo"Deploy to dev"
      }
       }
  }
}
