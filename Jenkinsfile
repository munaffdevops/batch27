@Library('shared-libraries') _

pipeline {
    agent any

    stages {
        stage('Build Application') {
            steps {
                mavenBuild()
            }
        }
    }
}
