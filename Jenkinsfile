```groovy
pipeline {
    agent any
    stages {
        stage('Clone Code') {
            steps {
git credentialsId: 'github', url: 'https://github.com/shivam7699/Machine-Learning-Project.git'
            }
        }
        stage('Setup/Run') {
            steps {
                sh 'echo "Deploy your code or run scripts here"'
// Example: sh 'python3 your_script.py'
            }
        }
    }
}
```
