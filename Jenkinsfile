pipeline {
    agent any
    stages {
        stage('build'){
            steps{
             sh 'mvn clean'
            }
            steps{
             sh 'mvn compile'         
            }
            steps{
             sh 'mvn install -DskipTests'   
            } 
        }
    }
}    
