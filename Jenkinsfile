pipeline {
    agent any

    tools {
        jdk 'JDK17'
    }

    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/NakkaTrilokesh/Jenkins_with_git.git'
            }
        }

        stage('Compile') {
            steps {
                sh 'javac Hello.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Hello'
            }
        }
    }
}

