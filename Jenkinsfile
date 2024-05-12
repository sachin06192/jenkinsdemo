pipeline {
    agent any
    tools {
        // Define the Maven installation to use
        maven 'Maven 3.9.6'
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn clean package'
            }
        }
    }
}
