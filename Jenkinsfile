pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "compiling the java source code BLA"
                sh "javac Hello.java"
            
            }
        }
        stage('run') {
            steps {
                echo "running the compiled java code blabla"
                sh 'java Hello'
            }
        }
    }
}
