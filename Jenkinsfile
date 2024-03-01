pipeline {
    agent any
    tools {
        maven 'maven'
    }

    stages {
        stage('bala') {
            steps {
               sh 'mvn compile'
            }
        }
        stage('murugan') {
            steps {
                sh 'mvn test'
            }
        }
        stage('kk') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
