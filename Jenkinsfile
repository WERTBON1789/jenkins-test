pipeline {
    agent any

    stages('build') {
        agent { docker { image 'gcc:latest' }}
        steps {
            sh 'gcc -o main main.c'
        }
    }
}
