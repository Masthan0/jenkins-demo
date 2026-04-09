pipeline {
    agent any  // Run on any available Jenkins agent

    stages {
        stage('Build') {
            steps {
                // Simulate a build step
                bat 'echo Build running...'
            }
        }

        stage('Test') {
            steps {
                // Simulate a test step
                bat 'echo Testing...'
            }
        }
    }

    post {
        always {
            // This runs at the end no matter success/failure
            bat 'echo Pipeline finished'
        }
    }
}
