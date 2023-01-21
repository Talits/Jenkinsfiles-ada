pipeline {
    agent any;
    stages {
        stage('color log') {
            when { branch 'main' }
              steps {
                sh "echo '\033[35mlog\033\033colorido!\033'"
              }
         }
         stage('color log') {
             when { branch 'feat/*' }
              steps {
                sh "echo '\033[31mlog\033\033colorido 2!\033'"
              }
        }
    }
}
    
        
