pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/sonhm3029/Flask-docker-CI-CD' 
                mail bcc: '', body: 'Thông báo build code', cc: '', from: '', replyTo: '', subject: 'Ok', to: 'hoangminhson29102001@gmail.com'
            }
        }
    }
    // post {
    //     always {
    //         emailext body: 'Thông báo gửi mail', recipientProviders: [[$class: 'DevelopersRecipientProvider'], [$class: 'RequesterRecipientProvider']], subject: 'Hoàng Minh Sơn'
    //     }
    // }
}