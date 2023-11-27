pipeline {
    agent any

    stages {
        stage('Print Value') {
            steps {
                script {
                    def myValue = "Hello, Jenkins!"
                    echo "My value is: ${myValue}"
                }
            }
        }
        // Add more stages as needed
        stage ('Invoke_pipeline') {
            steps {
                build job: 'banqup-mobile-app/develop-up', parameters: [
                string(name: 'param1', value: "value1")
                ]
            }
        }
    }
}
