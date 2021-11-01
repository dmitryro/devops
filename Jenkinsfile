pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                dir("/Users/dmitryroitman/Devel/temporary") {
                    sh "pwd"
                    sh 'touch test.txt'
                    sh 'echo "TEST Jenkins" >> test.txt'
                    sh 'rm -rf ./law-office'
                    sh 'git clone https://github.com/dmitryro/law-office.git'
                }
            }
        }
    }
}

