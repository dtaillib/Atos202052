pipeline {
    agent { 
        node {
            label 'jkagentdocker'
        }
    }
    stages {
        stage('construire') {
            steps {
                sh 'docker version'
            }
        }
    }
}
