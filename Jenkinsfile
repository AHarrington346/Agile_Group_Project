pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
              bat  "Hello.py"
            }
        }
        stage('Deploy') { 
            steps {
                echo "Deploy"
            }
        }
    }
}
