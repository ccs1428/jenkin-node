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
                sh 'npm install'
                sh 'npm run build'
            }
        }
        stage("install"){
            steps {
                sh 'npm install'

            }
        }
        stage("test"){
            steps {
                sh 'npm install'
                sh 'npm run test'
            }
        }

    }
}