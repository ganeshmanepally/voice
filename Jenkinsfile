pipeline{
    agent any

    stages {
        stage('Build'){
            steps {
                sh 'date'
                sh 'pwd'
            }
        }
        stage('Test'){
            steps{
                echo 'Testing....'
            }
        }
        stage('deployment'){
            steps{
                echo 'deployment completed'
            }
        }
    }
    post {
        always {
            cleanWs()
        }
    }
}
