pipeline {
    agent any

    stages {
        stage('Run Tests') {
            steps {
                // Run Selenium tests using Selenium Side Runner
                // Replace the command and parameters as per your setup
                echo 'pwd'
                sh 'selenium-side-runner -c "goog:chromeOptions.args=[--headless,--nogpu] browserName=chrome" *.side  --output-directory=results'
            }
        }
    }
}
