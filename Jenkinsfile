pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Build is complete"
            }
        }
    }
    post{
        always{
            emailext attachLog: true, body: 'This is an automated email by system', subject: 'Test mail from Jenkins', to: 'shiva291291@gmail.com,pratheja260418shiva@gmail.com'
        }
    }
}
