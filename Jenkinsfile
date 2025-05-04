pipeline {
    agent any

    stages {
        stage('Install Dependencies') {
            steps {
                sh 'pip install -r app/requirements.txt'
            }
        }

        stage('Unit Tests') {
            steps {
                sh 'pytest app/test_app.py'
            }
        }

        stage('Postman Tests') {
            steps {
                sh 'newman run postman/simple_test_collection.json'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t flask-app .'
            }
        }

        stage('Run Docker Container') {
            steps {
                sh 'docker run -d -p 5000:5000 --name flask-app flask-app'
            }
        }
    }
}
