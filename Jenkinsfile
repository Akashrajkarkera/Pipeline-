pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
                sh echo "Building the project"
                git credentialsId: 'github', url:'https://github.com/Akashrajkarkera/Pipeline-.git'
                sh 'ls'
            }
        } 
    }
}
