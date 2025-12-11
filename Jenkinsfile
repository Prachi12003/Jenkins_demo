
pipeline {
    agent any 
    stages {
        stage('Clone Repository') { 
            steps {
                echo 'Cloning the repository from GitHub...' 
                // Jenkins handles the actual cloning internally when configured with SCM
            }
        }
        stage('Build/Test (Example)') { 
            steps {
                echo 'Building or testing the code...'
                // You can add your build commands here, e.g., sh 'npm install' or sh 'make'
            }
        }
    }
}
