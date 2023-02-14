pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh './PES2UG20CS499-1'
                echo "Build Successful"
            }
        }
        stage('Test') {
            steps {
                sh './PES2UG20CS499-1'
            }
        }
    }
    post {
        always {
            echo "Pipeline completed"
        }
        failure {
            echo "Pipeline failed"
        }
    }
}
