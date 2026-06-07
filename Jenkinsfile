node {
    stage('Checkout') {
        git branch: 'main', url: 'https://github.com/luyawen2002-boop/calculator-quality-check.git'
    }

    stage('Show Files') {
        sh 'pwd'
        sh 'ls -la'
    }

    stage('Run Tests') {
        sh 'python3 -m pytest'
    }
}
