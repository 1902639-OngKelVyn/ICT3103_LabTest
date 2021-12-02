pipeline {
    agent any

    stages {
        stage('Build') { 
            steps {
                sh 'uwsgi --http: 3000 --wsgi-file wsgi.py' 
            }
        }
    }
}