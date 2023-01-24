import jenkins.model.*
jenkins = Jenkins.instance

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh javac myfile.java
                sh java myfile
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
