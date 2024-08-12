pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Build is complete"
            }
        }
        
        post{
            Success{
                emailext body: 'Email from Jenkins', subject: 'Test email', to: 'shiva291291@gmail.com,pratheja260418shiva@gmail.com'
            }
        }
        
}
