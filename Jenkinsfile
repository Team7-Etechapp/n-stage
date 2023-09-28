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
        stage ('2-John') {
            steps {
                sh 'ps -ef' 
                sh 'sudo systemctl status jenkins'
            }
        }
    }
}