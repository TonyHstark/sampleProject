pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo 'build started'
                bat "DevOpsLab.py"
            }
        }
        stage('Test') { 
            steps {
                echo 'test done'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'deploy done'
            }
        }
    }
}
