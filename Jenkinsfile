pipeline{
    agent { label 'maven-agent'}
    stages{
       stage('Git Checkout Stage'){
            steps{
                git branch: 'main', url: 'https://github.com/bhagyashreep032/java-example.git'
            }
         } 
       
       stage('Build Stage'){
            steps{
                sh 'mvn clean install'
            }
         }
    }
}
