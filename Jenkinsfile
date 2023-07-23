pipeline {
    agent any
    stages {
        stage('Make executable') {
            steps {
                sh('chmod +x ./algorithm.sh')
            }
        }
        stage('Execute') {
            steps {
                sh("./algorithm.sh")
            }
        }
        
    }
}