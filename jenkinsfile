pipeline {
    agent any
    stages {
        stage ('Git checkout branch') {
            steps {
                sh 'git clone https://github.com/welsh1lad/java_helloworld.git'
            }
        }
    }
    post {
   
        success {
            echo "SUCCESSFUL BUILD"
        }
        failure {
            echo "FAILED BUILD"
        }
        aborted {
            echo "BUILD ABORTED"
        }
    }
} 
 
