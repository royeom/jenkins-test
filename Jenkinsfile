pipeline {
    agent any 
    stages {
        stage('Fetch') {
            steps {
                sh 'git clone ssh://git@repo.ccos.dev:7999/ccos20/build-ccos.git'
            }
        }
    }
}
