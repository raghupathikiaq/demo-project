pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'checking the code'
            }
        }
     stages {
        stage('Build') {
            steps {
                echo 'build the HTML file'
                sh 'ls-l'
            }
        }
     stages {
        stage('Test') {
            steps {
                sh 'test -f index.html'
                echo 'Html test successfully'
            }
        }
     stages {
        stage('Deploy') {
            steps {
                echo 'deployed suceesffuly'
            }
        }
    }
}
