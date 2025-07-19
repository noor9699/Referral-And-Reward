pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'areeba', url: 'https://github.com/noor9699/Referral-And-Reward.git'
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
