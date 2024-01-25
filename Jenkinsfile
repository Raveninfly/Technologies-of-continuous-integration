pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Запуск shell-команди для стадії Build
                sh 'echo "Building project..."'
                // Тут можна додати інші команди, наприклад, компіляцію коду
            }
        }

        stage('Test') {
            steps {
                // Запуск shell-команди для стадії Test
                sh 'echo "Running tests..."'
                // Тут можна додати команди для запуску тестів
            }
        }

        stage('Deploy') {
            steps {
                // Запуск shell-команди для стадії Deploy
                sh 'echo "Deploying application..."'
                // Тут можна додати команди для розгортання додатку
            }
        }
    }
}
