pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "hello $USER"
                sh 'docker run hello-world'
            }                
        }
    }
}
