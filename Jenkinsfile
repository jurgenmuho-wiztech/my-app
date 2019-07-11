pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "mvn clean"
            }
        }
        stage('print'){
             steps {
                 echo "jurrgen"
             }
        }
        stage('--test--') {
            steps {
                sh "mvn clean test"
            }
        }
        stage('--package--') {
            steps {
                sh "mvn package"
            }
        }
    }
}
