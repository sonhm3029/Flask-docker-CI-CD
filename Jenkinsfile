pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/sonhm3029/Flask-docker-CI-CD' 
                mail bcc: '', body: 'Thông báo build code', cc: '', from: '', replyTo: '', subject: 'Son gui', to: 'hoangminhson29102001@gmail.com'
            }
        }
    }
}