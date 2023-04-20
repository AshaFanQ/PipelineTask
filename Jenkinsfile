pipeline {
    agent any
    environment {DIRECTORY_PATH = "/Users/47797/SIT753"
        
    }
    stages {
        stage('Build') {
            steps {
                echo "Fetch the code from this directory path: $DIRECTORY_PATH"
                echo "Compile the code and generate any necessary artifacts"
            }
        }
        
        stage('Test') {
            steps {
                echo "unit tests"
                echo "integration tests"
                bat 'java --version'
            }
        } 
        
        stage('Code Quality Check') {
            steps {
                echo "Check the quality of the code"
            }
        } 
        
        stage('Deploy') {
            steps {
                echo "Deploy the application to a testing environmentspecified by the environment variable"
            }
        }
        
        stage('Approval') {
            steps {
                echo "This is the Approval stage"
                sleep 10
            }
        }
        
        stage('Deploy to Production') {
            steps {
                echo "PRODUCTION_ENVIRONMENT = Jia Cheng Fan"
                echo "TESTING_ENVIRONMENT = QA testing"
            }
        }
        
    }
}
