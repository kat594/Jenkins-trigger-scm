pipeline {
    agent any

    stages {
        stage('Run Shell Script') {
            steps {
                sh 'chmod +x test.sh'
                sh './test.sh'
            }
        }
    }
}
