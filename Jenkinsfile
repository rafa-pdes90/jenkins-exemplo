pipeline {
    agent any 

    stages {
        stage('Build') {
            steps { 
                build 'Teste'
            }
        }
        stage('Ready?') {
            steps {
                input 'Are you ready for Kahoot?'
            }
        }
        stage('Kahoot!') {
            steps {
                echo 'KAHOOT!'
            }
        }
    }
}
