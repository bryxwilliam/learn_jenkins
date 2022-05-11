pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "echo 'Hello World Build Again'"
            }
        }
        stage('BuildMore') {
            steps {
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
