pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
              sh "echo Hello"
                sh "exit 1"
                // 
            }
        }
    }
    
    post { 
        success { 
            echo 'I will always say Hello again!'
        }
    }
}
