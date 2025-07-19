pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'feature-from-commit', url: 'https://github.com/noor9699/all_projects.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the entire repo...'
                bat 'dir' // or 'ls' for Linux
            }
        }
    }
}
