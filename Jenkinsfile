pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo Starting CI-CD Pipeline Locally'
                sh 'cd ~'
                sh 'pwd'
                sh 'cd /Users/kevinbodie/SoftwareDevelopment'
                sh 'pwd'
                sh 'ls -al'
                sh 'ls'
                
                sh 'python --version'
                sh 'which java'
                sh 'which python'
                
                sh '/Users/kevinbodie/anaconda3/bin/python --version'
                
                sh 'cd /Users/kevinbodie/SoftwareDevelopment/Spring/testing-web'
                sh './mvnw test'
            }
        }
    }
}
