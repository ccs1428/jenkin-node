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
                sh 'npm run build'
            }
        }
        stage("install"){
            steps {
                sh 'sudo apt install npm'

            }
        }
        stage("test"){
            steps {
                sh 'sudo apt install npm'
                sh 'npm run test'
            }
        }

    }
}