pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                configFileProvider([configFile(fileId: 'dev-azure-com-kth-integration-integration', targetLocation: '.m2/settings.xml')]) {
                }
            }
        }
    }
}
