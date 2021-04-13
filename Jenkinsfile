pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
              sh "echo Hello"
               // sh "exit 1"
                // 
            }
        }
    }
    
    post { 
        success { 
            
            script {
            if ( env.CHANGE_ID )   {
            echo 'I will always say Hello again!'
                
            }
            }
        }
    }
}
