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
                bat "mvn clean test"
            }
        }
        stage('--package--') {
            steps {
                bat "mvn package"
            }
        }
    }
}
