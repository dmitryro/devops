pipeline {
    agent any

    stages {
        stage('Initial') {
            steps {
                dir("/Users/dmitryroitman/Devel/temporary") {
                    sh "pwd"
                    sh 'echo "TEST IT Jenkins" > jenkins.txt'
                    sh 'rm -rf ./law-offices'
                    sh 'git clone git@github.com:dmitryro/law-office.git'
                }
            }
        }
    }
}

