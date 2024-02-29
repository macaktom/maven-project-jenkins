pipeline {
    agent any
    stages {
        stage('Checkout project from SCM') { 
            steps {
                git branch: 'master', url: 'https://github.com/macaktom/maven-project-jenkins' 
            }
        }
        stage('Test webhook') {
            steps {
                sh 'echo "Webhook works"'
            }
        }
    }
}