pipeline {
    agent any 
    stages {
        stage('clone repo') { 
            steps {
                bat "rmdir /Q /S my-app"
                bat "git clone https://github.com/gkumar1987/my-app.git"
                bat "mvn clean"
            }
        }
    }
}