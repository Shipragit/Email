pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build is complete'
            }
        }
        stage('Test') {
            steps {
                echo 'Test is complete'
            }
        }
        stage('Deployment') 
            steps {
                echo 'Deployment is complete'
            }
        }
    }
        post{
            Success{
                emailext body: 'Email from Jenkins', subject: 'Test email', to: 'shiva291291@gmail.com,pratheja260418shiva@gmail.com'
            }
        }
        
}
