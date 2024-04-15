pipeline{
    agent any
    stages {
        stage("checkout"){
            steps {
                checkout scm
            }
        }
        stage("build"){
            steps {
                sh 'apt install npm'
                sh 'npm run build'
            }
        }
        stage("install"){
            steps {
                sh 'apt install npm'

            }
        }
        stage("test"){
            steps {
                sh 'apt install npm'
                sh 'npm run test'
            }
        }

    }
}