pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/sonhm3029/Flask-docker-CI-CD' 
                emailext body: 'Thông báo build code',
                    subject: 'Test Subject',
                    to: 'hoangminhson29102001@gmail.com'
            }
        }
    }
}