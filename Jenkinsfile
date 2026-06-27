pipeline {
    agent any
    stages {
        stage('hello name') {
            steps {
                sh "chmod +x hello.sh" 
                sh "./hello.sh mohammed"
            }
        }
        stage('Hello object') {
            steps {
                sh "chmod +x hello.sh"
                sh "./hello.sh jenkins"
            }
        }
    }
}
