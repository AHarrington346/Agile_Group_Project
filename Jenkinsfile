pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
              bat "C:\\Users\\aaron\\Downloads\\python.exe Hello.py"
            }
        }
        stage('Deploy') { 
            steps {
                echo "Deploy"
            }
        }
    }
}
