pipeline {
    agent any

    stages {
        stage('Print Value') {
            steps {
                script {
                    def myValue = "Hello, Jenkins!"
                    echo "My value is: ${myValue}"
                    sleep 25
                }
            }
        }
        // Add more stages as needed
    }
}
