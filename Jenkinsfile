pipeline{
        
        agent any
        
        stages {
            
            stage ('maven tool'){
                
                step{
                withMaven(maven : 'M3')
                
                }
                
            }
            
            stage('clean'){
                
                step{
                 
                 sh "mvn clean"   
                    
                }
               
            }
            stage('compile'){
                
                step{
                 
                 sh "mvn compile"   
                    
                }
               
            }
            stage('install '){
                
                step{
                 
                 sh "mvn install -DskipTests"   
                    
                }
               
            }
            
            
            
