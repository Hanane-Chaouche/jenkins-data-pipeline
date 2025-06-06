pipeline {
    agent any

    environment {
        JAVA_HOME = 'C:\\Program Files\\Java\\jdk-17'
        PATH = "${JAVA_HOME}\\bin;${env.PATH}"
    }

    stages {
        stage('Build') {
            steps {
                script {
                    bat 'pip install pandas'            // Installer pandas
                    bat 'python data_analysis.py'       // Exécuter le script Python
                }
            }
        }
    }
}
