pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "M3"
    }

    stages {
        stage('gitclone') {
            steps {
                // Get some code from a GitHub repository
                git clone 'https://github.com/gouthamyeldandi/angular-with-spring-boot-and-mongo.git'

            }
        }    
            stage('build') {
              steps {
                
                sh 'mvn clean install -DskipTests'

              }

            }
    }
}
    
    
    
    
