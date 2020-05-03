pipeline {
    agent any 
    stages {
        stage('cloning and cleanig') { 
            steps {
               bat "mvn clean"
            }
        }
        stage('Test') { 
            steps {
                bat "mvn test"
            }
        }
        stage('Deploy') { 
            steps {
                bat "mvn package"
            }
        }
    }
}
