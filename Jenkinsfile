pipeline {
    agent {
        docker {
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'python3 app.py' 
            }
        }
    }
}