
pipeline {
    agent any

    stages {
       
        
        stage('Stage 1') {
            steps {
                sh ''' 
                   docker build -t moataz .
                   docker run -p 3000:3000  -d  moataz
                '''
            }
        }
        
    }
}
