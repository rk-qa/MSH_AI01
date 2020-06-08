node
{
 stage('SCM Checkout')
  {
     git 'https://github.com/rk-qa/MSH_AI01'
  }
  
   stage('Compile-Package')
  {
  def mvnHome = tool name: 'localMaven', type: 'maven'
  
  sh "${mvnHome}/bin/mvn package" 
  }
  
}
