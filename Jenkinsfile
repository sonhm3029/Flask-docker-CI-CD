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
            emailext body: 'Thông báo gửi mail', recipientProviders: [[$class: 'DevelopersRecipientProvider'], [$class: 'RequesterRecipientProvider']], subject: 'Hoàng Minh Sơn'
        }
    }
}