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
                sh 'validate'
            }
        }
        stage('Plan') {
            steps {
                sh 'plan'
            }
        }
        stage('apply') {
            steps {
                sh 'apply'
            }
        }
    }
}
