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
                sh 'npm install'
            }
        }

        stage('Build App'){
            steps{
                sh 'npm run build'
            }
        }
    }
}