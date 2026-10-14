pipeline{
    agent any

    stages{
        stage('checkout'){
            steps{
                git branch: 'main',
                url:'https://github.com/HariraamOx7/simple-react-app2.git'
            }
        }

        stage('Install Dependency'){
            steps{
                bat 'npm install'
            }
        }

        stage('Build App'){
            steps{
                bat 'npm run build'
            }
        }
    }
}