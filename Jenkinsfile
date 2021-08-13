properties = null
def loadProperties() {
    node {
        properties = readProperties file: 'MyCustom'
    }
}

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                script{
                    loadProperties()
                }
                echo "Hello ${properties.name}"
                echo "${JENKINS_HOME}"
            }
        }
    }
}
