pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'javac Hello.java'
            }
        }
      stage('Run') {
            steps {
                echo 'Running...'
                sh 'java Hello'
            }
        }
    }
}
