pipeline {
    agent any;
    stages {
        stage('color log') {
          steps {
            script {
                    if (env.BRANCH_NAME == 'main') {
                        sh "echo '\033[35mlog\033\033colorido!\033'"
                    }  else {
                        sh "echo 'Hello from ${env.BRANCH_NAME} branch!'"
                    }
            }
         }
        }
    }
}
    
        
