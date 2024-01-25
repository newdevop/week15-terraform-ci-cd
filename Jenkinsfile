pipeline {
    agent any

    stages {
        stage('Initialize') {
            steps {
                sh 'terraform init'
            }
        }
        stage('test') {
            steps {
                echo 'Hello test'
            }
        }
         stage('package') {
            steps {
                echo 'Hello package'
            }
        }
    }
}
