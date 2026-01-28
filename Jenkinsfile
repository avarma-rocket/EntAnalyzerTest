pipeline {
    agent any
    
    triggers {
        
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
