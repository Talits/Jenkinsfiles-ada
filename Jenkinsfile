pipeline {
    agent any;
    options {
       ansiColor('xterm')
    }
    stages {
        
        stage('color log') {
          when {
            branch "main"
          }
          steps {
            sh "echo '\033[35mlog\033\033colorido!\033'"
          }
        }
      
        stage('color log feature') {
           when {
              branch "feat/*"
           }
          steps {
            sh "echo '\033[35mlog\033\033feature!\033'"
          }
        }
    }
} 
