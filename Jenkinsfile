pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo 'build started'
                sh "DevOpsLab.py"
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
