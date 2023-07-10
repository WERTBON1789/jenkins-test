pipeline {
    agent { docker { image 'gcc:latest' }}

    stages {
        stage('build') {
            steps {
                echo "Ding"
                sh 'gcc -o main main.c'
            }
        }
    }
}
