node {
    stage('Checkout') {
        git branch: 'main', url: 'https://github.com/your-repo/your-project.git'
    }
    stage('Build') {
        sh 'mvn clean install'
    }
    stage('Test') {
        sh 'mvn test'
    }
    stage('Deploy') {
        echo 'Deploying to production...'
    }
}
