pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'javac Pipeline.java' // Compile your Java file
            }
        }
        stage('Run') {
            steps {
                sh 'java Pipeline' // Run the compiled Java class
            }
        }
    }
}