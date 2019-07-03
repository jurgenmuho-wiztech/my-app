pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                bat "mvn clean"
            }
        }
        stage('print'){
             steps {
                 echo "jurrgen"
             }
        }
        stage('--test--') {
            steps {
                bat label: '', script: '''mvn test'''
            }
        }
        stage('--package--') {
            steps {
                bat "mvn package"
            }
        }
    }
}
