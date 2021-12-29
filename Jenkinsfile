pipeline{
    agent any
    stages{
        stage('gitclone'){
            steps{
                git 'clone https://github.com/gouthamyeldandi/angular-with-spring-boot-and-mongo.git'
            }
            stage('build'){
            steps{
                sh 'mvn clean install -DskipTests'
            }
    }
}
    
    
    
    
    
    
    
    
