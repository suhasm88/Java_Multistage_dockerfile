pipeline {
    agent any
        stages {
             stgae {
               steps {
                 Script {
                    sh 'docker build -t my-firstpipe .'
                    sh 'docker run -it -d --name my-jenk-cont -p 8087:8080 my-firstpipe'
                    }
                  }
        }
       }
  } 
