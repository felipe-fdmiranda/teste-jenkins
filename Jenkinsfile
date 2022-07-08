pipeline {
    agent any
    stages {
        stage('Construindo e subindo container no host') {
            steps {
                echo 'docker-compose up -d --build' > /hostpipe/pipe
            }
        }
    }
}