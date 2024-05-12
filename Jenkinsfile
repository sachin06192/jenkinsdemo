pipeline {
    agent any
    tools {
        // Define the Maven installation to use
        maven 'Maven 3.9.6'
    }
    stages {
        stage('Build') {
            steps {
                dir('jenkinsdemo/jenkinsdemojava') {
                    bat 'mvn clean package'
                }
            }
        }
    }
}
