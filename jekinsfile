pipeline{
    
    tools{
        maven 'mymaven'
    }
    agent any
    
    stages{
        stage('Clone the repo')
        {
            steps{
            git 'https://github.com/vabs121/EdurekaDevOpsCode.git'
            }
        }
        
        stage ('Build the code')
        {
            steps{
            sh 'mvn clean install package'
            }
        }
  
    }
}
