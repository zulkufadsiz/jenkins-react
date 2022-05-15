pipeline {
    agent any
    stages{
        stage('Build'){
  
            steps {
                dir('jenkins-react'){
                    sh 'pwd'
                    sh 'ls'
                }
                 sh 'cd jenkins-react'
                 sh '/usr/local/bin/npm install'
            }
        }
    }
}
