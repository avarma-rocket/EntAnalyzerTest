pipeline {
    agent any
    
    triggers {
        // Poll the repository every 5 minutes
        pollSCM('* * * * *')
    }
    
    stages {
        stage('Hello World') {
            steps {
                echo 'Hello World!'
            }
        }
    }
    
    post {
        always {
            echo 'Build finished!'
        }
    }
}
