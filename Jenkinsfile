pipeline {
    agent any

    stages {
        stage ('Compile Stage') {
            steps {
                echo 'Compile Stage'
            }          
        }
        stage ('Testing Stage') {
            steps {
                echo 'Testing Stage'
            } 
        }
        stage ('Deployment Stage') {
            steps {
                echo 'Deployment Stage'
            }
        }
    }
    
    post {
        always {
            echo 'This will always run'
        }
        success {
            echo 'This will run only if successful'
        }
        failure {
            echo 'This will run only if failed'
        }
        unstable {
            echo 'This will run only if the run was marked as unstable'
        }
        changed {
            echo 'This will run only if the state of the Pipeline has changed'
            echo 'For example, if the Pipeline was previously failing but is now successful'
        }  
    }
}
