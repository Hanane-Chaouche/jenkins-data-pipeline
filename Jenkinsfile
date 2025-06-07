pipeline {
    agent any

       
    stages {
        stage('Build') {
            steps {
                script {
                  bat 'python data_analysis.py'       // Exécuter le script Python
                }
            }
        }
    }
}
