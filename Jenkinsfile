pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
				echo "Current workspace is ${env.WORKSPACE}"
                echo 'Hello World'
            }
        }
         stage('Build') {
            steps {
                echo 'Building'
            }
        }
         stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
         stage('Test') {
            steps {
                echo 'Testing'
            }
        }
         stage('Release') {
            steps {
                echo 'Releasing'
            }
        }
    }
}
