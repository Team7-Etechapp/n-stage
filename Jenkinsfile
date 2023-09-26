pipeline {
    agent any
    stages {
        stage ('1-Sherack') {
            steps {
                sh '''
                ps -ef
                sudo systemctl status jenkins
                '''
            }
        }
        stage ('2-Abby') {
            steps {
                sh '''
                ps -ef
                sudo systemctl status jenkins
                '''
            }
        }
    }
}