pipeline {
    agent any
    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "M3"
    }
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
