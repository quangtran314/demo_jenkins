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
                cd myapp
                python3 hello.py
                python3 hello.py --name=Quang
                '''
            }
        }
    }
}
