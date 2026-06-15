pipeline{
    agent any

    stages{
        stage("Restore packages"){
            steps{
                bat 'dotnet restore'
            }
        }
        stage("Builds"){
            steps{
                bat 'dotnet build'
            }
        }
        stage("Test"){
            steps{
                bat 'dotnet test'
            }
        }
    }
}