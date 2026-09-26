pipeline {
    agent any

    stages {
        stage('Run Shell Script') {
            steps {
                sh 'chmod +x script.sh'
                sh './test.sh'
            }
        }
    }
}
