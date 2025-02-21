pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello-World'
            }
        }
        
        stage('Build') {
            steps {
                echo 'Building'
                bat 'javac Fibonacci.java'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        
        stage('Run') {
            steps {
                echo 'In run stage...'
                bat 'java Fibonacci'
            }
        }
    }
}
