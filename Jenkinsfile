pipeline {
    agent any
    stages {        
        stage ('\u273F Build Stage') {
            steps {
                echo 'Build Stage'
            } 
        }
        ansiColor('xterm') {
            // Just some echoes to show the ANSI color.
            stage "\u001B[31mI'm Red\u001B[0m Now not"
        }
        stage ('\u2600 Testing Stage') {
            steps {
                echo 'Testing Stage'
            } 
        }

    }
}
