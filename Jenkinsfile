pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                echo 'Code checked out successfully'
            }
        }

        stage('Run Script') {
            steps {
                sh 'python3 app.py'
            }
        }
        stage('Test Stage') {
    steps {
        echo 'This is a test stage'
    }
}

    }
}
