pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 100, unit: 'SECONDS')
    }
    stages {
        stage('Scripted pipeline created in github') {
            steps {
                echo 'Hello Naresh'
                git branch: 'main', url: 'https://github.com/nareshbashipangu/SpringPetClinic.git'
            }
        }
    }
}
