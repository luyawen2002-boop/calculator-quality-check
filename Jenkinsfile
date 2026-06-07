node {
    stage('Checkout') {
        git branch: 'main', url: 'https://github.com/luyawen2002-bop/calculator-quality-check.git'
    }

    stage('Run Tests') {
        sh 'python3 -m pytest'
    }
}
