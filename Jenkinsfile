pipeline {
    agent any

    stages {
        stage('NPM Install') {
            steps {
                script {
                    // Checkout Repository
                    git 'https://github.com/your-username/your-repo.git'

                    // Setup NodeJS Version
                    tool 'NodeJS_18'

                    // Install Dependencies
                    sh 'npm install'
                }
            }
        }
    }
}
