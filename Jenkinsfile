Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any
    stages {
      stage('Build') {
            steps {
                bat 'echo %date% %time% build lab_jenkins >> d:/works/jenkins/lab_jenkins.log'
            }
        }
        stage('Test') {
            steps {
                bat 'echo %date% %time% test lab_jenkins >> d:/works/jenkins/lab_jenkins.log'
            }
        }
        stage('Deploy') {
            steps {
                bat 'echo %date% %time% deploy lab_jenkins >> d:/works/jenkins/lab_jenkins.log'
            }
        }
    }
    post {
        always {
            bat 'echo %date% %time% post lab_jenkins >> d:/works/jenkins/lab_jenkins.log'
        }
    }
}
