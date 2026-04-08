pipeline {
    agent any

    parameters {
        string(name: 'ENV', defaultValue: 'dev', description: 'Environment')
    }

    stages {

        stage('Checkout') {
            steps {
                echo "Code already checked out by Jenkins"
            }
        }

        stage('Build') {
            steps {
                echo "Building in ${ENV} environment..."
            }
        }

        stage('Test') {
            steps {
                echo "Testing in ${ENV} environment..."
            }
        }
    }
}
