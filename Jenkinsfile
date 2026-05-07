pipeline{

    agent{
        docker{
            image 'node:18'
        }
    }
    stages{
        stage('Install Dependencies'){
            steps{
                sh 'npm install'
            }
        }

        stage('Build'){
            steps{
                echo 'Build Successful'
            }
        }

        stage('Run'){
            steps{
                sh 'npm start'
            }
        }
    }
}