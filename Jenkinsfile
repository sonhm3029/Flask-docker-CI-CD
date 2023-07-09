pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/sonhm3029/Flask-docker-CI-CD' 
                mail bcc: '', body: 'Xin chào đây là mail từ jenkins', cc: '', from: '', replyTo: '', subject: '', to: 'hoangminhson29102001@gmail.com'
            }
        }
    }
}