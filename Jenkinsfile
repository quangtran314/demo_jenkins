pipeline {
    agent { 
        node {
            label 'cloud_agent'
            }
    }
    stages {
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                python3 helloworld.py
                '''
            }
        }
    }
}
