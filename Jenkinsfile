pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
              git branch: 'main', url: 'https://github.com/gotadsuraj570-design/java-pipeline.git'
            }
        }
         stage('Compile') {
            steps {
              bat 'javac HelloWorld4.java'
            }
        }
         stage('Run') {
            steps {
                bat 'javac HelloWorld4'
            }
        }
    }
}
