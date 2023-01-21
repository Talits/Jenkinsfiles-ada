
pipeline {
    agent any;
    stages {
        when {
            branch "main"
        }
        stage('color log') {
          steps {
            sh "echo '\033[35mlog\033\033colorido!\033'"
          }
        }
        when {
            branch "feat/*"
        }
        stage('color log feature') {
          steps {
            sh "echo '\033[35mlog\033\033feature!\033'"
          }
        }
    }
}  
