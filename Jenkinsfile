pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "compiling the java source code"
                sh "javac Hello.java"
            
            }
        }
        stage('run') {
            steps {
                echo "running the compiled java code"
                sh 'java Hello'
            }
        }
    }
}
