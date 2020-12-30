pipeline {
    agent { docker 
           { image 'python:3.5.1'
             args '-i --entrypoint='
           }
          }
    stages {
        stage('Test') {
            steps {
                sh 'python --version'
            }
        }
    }
}
