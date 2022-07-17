pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('Build') {
            steps {
                echo 'Building the project...OK!!'
                gradle build 
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploy to staging...OK!!'
                gradle run
            }
        }
        
        stage('Test') {
            steps {
                echo 'Performing test...OK!'
            }
        }
        
        stage('Release') {
            steps {
                
                echo 'Release to production...OK!!'
            }
        }
    }
}
