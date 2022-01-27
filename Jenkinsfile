pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Hello World! from branch " + env.BRANCH_NAME
            }
        }
    }
}
