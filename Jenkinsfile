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
            emailext attachLog: true, body: 'This is an automated email by system', subject: '$PROJECT_NAME - Build # $BUILD_NUMBER - $BUILD_STATUS!', to: 'shiva291291@gmail.com,pratheja260418shiva@gmail.com'
        }
    }
}
