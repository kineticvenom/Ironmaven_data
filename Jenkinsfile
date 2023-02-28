node {
    stage('Checkout') {
        git branch: 'main', url: '/home/wasadmin/Software/repos/Ironmaven_data.git'
    }
    
    stage('Gradle build') {
        sh 'gradle build'
    }
}