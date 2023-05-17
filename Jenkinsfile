pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Perform build steps here with polling'
                //sh 'mvn clean compile'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Perform test steps here'
                //sh 'mvn test'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Perform deployment steps here'
                //sh 'mvn deploy'
            }
        }
    }
}
