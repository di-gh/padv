pipeline {
    agent any

    stages {
        stage('1-Build') {
            steps {
                echo "Start of Stage Build"
                echo "Building......."
                sh   "python3 --version"
                echo "End of Stage Build"
            }
        }
        stage('2-Test') {
            steps {
                echo "Start of Stage Test"
                echo "Testing......."
                sh "ls -la"
                echo "End of Stage Test"
            }
        }
        stage('3-Deploy') {
            steps {
                echo "Start of Stage Deploy"
                echo "Deploying......."
                sh '''
                echo "line1"
                cowsay "Deploy!"
                echo "line2"
                '''
                echo "End of Stage Deploy"
            }
        }
        stage('4-Notify') {
            steps {
                echo "Tralala!"
            }
        }
    }
}
