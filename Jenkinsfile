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
                echo " Running on the environment ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
        
        stage('Deploy'){
            steps {
                sh 'cd /home/ec2-user'
                sh 'cp index.html /apache-tomcat-7.0.93/webapps'
                  }
       }
    }
}   
    
