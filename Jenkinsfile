node {
    stage('Show Files') {
        sh 'pwd'
        sh 'ls -la'
    }

    stage('Run Tests') {
        sh 'python3 -m pytest'
    }
}
