pipeline {
    agent any

    stages {
        stage('Initial') {
            steps {
                dir("/Users/dmitryroitman/Devel/temporary") {
                    sh "pwd"
                    dir("law-office") {
                        deleteDir()
                    }
                    sh 'echo "TEST IT NOW Jenkins" > jenkins.txt'
                    sh 'git clone git@github.com:dmitryro/law-office.git'
                }
            }
        }
    }
}

