pipeline{
    agent any
    options {
        buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '', daysToKeepStr: '1', numToKeepStr: '1')
        }
    stages{
        stage('branch test'){
            steps{
                echo "this is the ${env.BRANCH_NAME} "
            }
        }
    }
}
