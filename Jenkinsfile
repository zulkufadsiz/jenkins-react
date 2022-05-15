pipeline {
    agent any
    enviroment {
      PATH='/usr/local/bin:$PATH'
    }
    stages{
        stage('Build'){
            steps {
                 sh 'npm install'
            }
        
        }
    }
}
