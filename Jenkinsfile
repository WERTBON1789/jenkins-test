pipeline {
    agent any

    stages {
        stage('build') {
            agent { docker { image 'gcc:latest' }}
            steps {
                sh 'gcc -o main main.c'
            }
        }
    }
}
