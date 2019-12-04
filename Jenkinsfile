pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
              bat "C:\\Program Files (x86)\\Python\\python.exe Hello.py"
            }
        }
        stage('Deploy') { 
            steps {
                echo "Deploy"
            }
        }
    }
}
