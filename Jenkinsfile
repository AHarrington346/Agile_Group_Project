pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
              bat "C:\\Program Files (x86)\\Python\\python.exe C:\\Users\\aaron\\Downloads\\Hello.py"
            }
        }
        stage('Deploy') { 
            steps {
                echo "Deploy"
            }
        }
    }
}
