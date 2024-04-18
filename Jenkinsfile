pipeline {
    agent any
    stages {
        stage('Compile') {
            steps {
                sh 'javac Hello.java' // Compile the Java source file
            }
        }
        stage('Run') {
            steps {
                sh 'java Hello' // Run the compiled class
            }
        }
    }
}
