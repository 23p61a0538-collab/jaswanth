pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'devopscsea',
                    url: 'https://github.com/23p61a0538-collab/jaswanth.git'
            }
        }

        stage('Build') {
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
