pipeline {
    agent any

    stages {
        stage('Initialize') {
            steps {
                sh 'terraform init'
            }
        }
        stage('format code') {
            steps {
                sh 'terraform fmt'
            }
        }
         stage('validate') {
            steps {
                sh 'terraform validate'
            }
        }
        stage('Plan') {
            steps {
                sh 'terraform plan'
            }
        }
        stage('apply') {
            steps {
                sh 'terraform apply'
            }
        }
    }
}
