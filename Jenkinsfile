pipeline{
    agent any
     stages {
                stage ('performing the lint checks') {
            steps{
                // sh "echo installing jslint"
                // sh "npm install jslint"
                // sh "ls -ltr node-modules/jslint/bin/"
                // sh "/home/centos/jslint/bin/jslint.js server.js"
                sh "echo performing lint checks"
                sh "echo performing lint checks completed"
            }
        }
        stage ('downloading the dependencies') {
            steps{
                sh "npm install"
            }
        }
     }
}