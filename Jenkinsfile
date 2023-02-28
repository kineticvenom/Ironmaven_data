node {
    stage('Checkout') {
        git branch: 'main', url: '~/Software/repos/Ironmaven_data.git'
    }
    
    stage('Gradle build') {
        sh 'gradle build'
    }
}