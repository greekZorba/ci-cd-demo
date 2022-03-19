pipeline {
    agent any

    stages {
        stage('Build Docker image') {
            steps {
                echo 'Testing..'
            }
//             steps {
//                 script {
//                     sh "./gradlew installDist"
//                 }
//             }
//             container('docker') {
//                 docker.build("ci-cd-demo")
//             }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying..'
//                 container('docker') {
//                     docker.run()
//                 }
            }
        }
    }
}