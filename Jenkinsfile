pipeline {
    agent any

    stages {
        
        stage('Restore') {
            steps {
                // Restore NuGet packages
                sh 'dotnet restore'
            }
        }

        stage('Build') {
            steps {
                // Build the .NET Core application
                sh 'dotnet build --configuration Release'
            }
        }

        stage('Publish') {
            steps {
                // Publish the .NET Core application
                sh 'dotnet publish --configuration Release --output ./publish'
            }
        }

        
    }
}
