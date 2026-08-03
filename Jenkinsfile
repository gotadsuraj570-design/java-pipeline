pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
               git branch: 'main' 
            }
        }
         stage('Compile') {
            steps {
                echo 'Hello World'
            }
        }
         stage('Run') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
