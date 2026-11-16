pipeline {
    agent any

    stages {
        
        stage('Checkout') {
            steps {
                echo 'checking the code'
            }
        }
    
        stage('Build') {
            steps {
                echo 'build the HTML file'
                sh 'ls -l'
            }
        }
     
        stage('Test') {
            steps {
                sh 'test -f index.html'
                echo 'Html test successfully'
            }
        }
     
        stage('Deploy') {
            steps {
                echo 'deployed suceesffuly'
            }
        }
    }
}
