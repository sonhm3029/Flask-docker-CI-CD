pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/sonhm3029/Flask-docker-CI-CD' 
            }
        }
    }
    post {
        always {
            mail bcc: '', body: 'Thông báo build code', cc: '', from: '', replyTo: '', subject: 'Ok', to: 'hoangminhson29102001@gmail.com'
        }
    }
}