pipeline { 
    agent any 
    options {
        buildDiscarder(logRotator(numToKeepStr: '5'))
    }
    stages {
        stage('Build') { 
            steps { 
                echo "My name is rodrigue"
            }
        }
        stage('Test'){
            steps {
                sh 'echo "you and me"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "it is deployed"'
            }
        }
    }
}
