pipeline {
    stages {
        stage('build') {
            docker.withServer('tcp://dind:2376') {
                docker.image('gcc:latest') {
                    steps {
                        echo "Ding"
                        sh 'gcc -o main main.c'
                    }
                }
            }
        }
    }
}
