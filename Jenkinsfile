pipeline {
    agent any

    tools {
        maven "MAVEN_HOME"
        nodejs "NODE_HOME"
    }

    stages {
        stage('Build') {
            steps {
                //  GitHub repository
               git 'https://github.com/HrishiReddy/react.git'

                
                 bat "npm install && npm run build"
            }
               
           
        }
    
   }
}
