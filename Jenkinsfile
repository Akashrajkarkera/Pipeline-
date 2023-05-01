pipeline {
    agent any

    stages {
        stage('Fetch Jenkinsfile') {
            steps {
                script {
                    git url: 'https://github.com/Akashrajkarkera/Pipeline-.git', branch: 'main'
                    sh "cp Jenkinsfile jenkinsfile_dir/"
                }
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building the project"'
            }
        }

        // Add more stages for testing, deploying, etc.
    }
}
