
Jenkinsfile (Declarative Pipeline)

pipeline {
    agent any
    stages {
      stage('Build') {
            steps {
                sh 'echo %date% %time% build lab_jenkins >> d:\works\jenkins\lab_jenkins.log'
            }
        }
        stage('Test') {
            steps {
                sh 'echo %date% %time% test lab_jenkins >> d:\works\jenkins\lab_jenkins.log'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo %date% %time% deploy lab_jenkins >> d:\works\jenkins\lab_jenkins.log'
            }
        }
    }
    post {
        always {
            sh 'echo %date% %time% post lab_jenkins >> d:\works\jenkins\lab_jenkins.log'
        }
    }
}

