pipeline {
    agent any
    stages {
        stage("Get the Branch") {
            steps {
                script {
                    echo "Branch name is ${env.BRANCH_NAME}"
                }
            }
        }
    }
}
