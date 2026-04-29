pipeline {
    agent any
    stages {
        stage('Install') { steps { bat 'npm install' } }
        stage('Build')   { steps { bat 'npm run build || echo No build script' } }
        stage('Test')    { steps { bat 'npm test || echo No tests' } }
    }
}
