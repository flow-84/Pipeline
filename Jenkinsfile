pipeline {
    agent none // Kein Agent hier, weil wir später einen spezifischen Agent zuweisen werden

    stages {
        stage('Stage 1') {
            agent { label 'your-agent-label' } // Ersetzen Sie 'your-agent-label' mit dem Label Ihres neuen EC2-Agents
            steps {
                echo 'Ausführung der Stage 1'
            }
        }
        stage('Stage 2') {
            agent { label 'your-agent-label' }
            steps {
                echo 'Ausführung der Stage 2'
            }
        }
        stage('Stage 3') {
            agent { label 'your-agent-label' }
            steps {
                echo 'Ausführung der Stage 3'
            }
        }
    }
}
