Jenkinsfile (Declarative Pipeline)

pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello this is the first pipeline"'
                sh '''
                    echo "Multiple line step!"
                    ls -lah
                  '''
            }
        }
    }
}
