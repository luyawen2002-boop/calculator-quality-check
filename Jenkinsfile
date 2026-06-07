node {
    stage('Checkout') {
        checkout scm
    }

    stage('Run Tests') {
        sh 'python3 -m pytest'
    }
}
