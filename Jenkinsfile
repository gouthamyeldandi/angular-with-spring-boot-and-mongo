pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "M3"
    }

    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git 'hhttps://github.com/gouthamyeldandi/angular-with-spring-boot-and-mongo.git'

                // Run Maven on a Unix agent.
                sh "mvn clean compile"

            }

        }
        stage('run') {
            steps {
                
                sh "mvn install -DskipTests"

            }

        }
    }
}
