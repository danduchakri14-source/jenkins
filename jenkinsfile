pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/danduchakri14-source/jenkins.git'
            }
        }
        stage('Show IP') {
            steps {
                sh './get_ip.sh'
            }
        }
    }
}
 
