pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/raj-cmd971/skill_lab_devops.git'
            }
        }

        stage('Hello') {
            steps {
                echo "hello from jenkins pipelines!"
            }
        }

        stage('Goodbye') {
            steps {
                echo "jenkins finished successfully"
            }
        }
    }
}



