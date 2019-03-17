//scripted
/*node {
    echo "${env.JENKINS_URL}"
    echo "${env.USER}"
    
    echo "Hello World"
    echo "new pipeline script"
    echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
}*/

//Declarative
pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo " Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
    
}
