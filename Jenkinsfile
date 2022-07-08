pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                docker-compose up -d --build
            }
        }
    }
}