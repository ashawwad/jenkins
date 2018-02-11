pipeline {
    agent any

    stages {
        wrap([$class: 'AnsiColorBuildWrapper']) {
            stage ('\u001B[31m Build Stage') {
                steps {
                    echo 'Build Stage'
                } 
            }
        }

        stage ('Testing Stage') {
            steps {
                echo 'Testing Stage'
            } 
        }

    }
}
