pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/AsthaDave/HelloWorldJava.git'
            }
        }
        stage('Build') {
            steps {
                sh 'javac HelloWorld.java' // Modify based on project type
            }
        }
        stage('Test') {
            steps {
                sh 'java HelloWorld'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo Deploying application...'
            }
        }
    }
}
