pipeline {
    agent any

    stages {
        stage('Print Value') {
            steps {
                script {
                    echo "Chosen option: $params.TYPE_OF_RUNNING $TYPE_OF_RUNNING"
                    def myValue = "Hello, Jenkins!"
                    echo "My value is: ${myValue}"
                    sleep 25
                }
            }
        }
        // Add more stages as needed
    }
}
