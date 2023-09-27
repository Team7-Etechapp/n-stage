pipeline {
    agent any
    stages {
        stage ('1-Abby') {
            steps {
                sh '''
                ps -ef
                sudo systemctl status jenkins
                '''
            }
        }
    }
}