pipeline {
    agent any
    tools { 
        maven 'Maven' 
        jdk 'JAVA' 
    }
    stages {
        stage ('Build') {
            steps {
                echo 'This is a minimal pipeline.'
                sh ''' java --version; 
                mvn --version '''
            }
        }
    }
}
