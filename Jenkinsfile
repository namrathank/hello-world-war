  pipeline { 
    agent { label 'slave2' } 
    stages { 
        stage ('Checkout') { 
            steps {
                sh "pwd"
                sh "rm -rf hello-world-war"
                sh "git clone https://github.com/namrathank/hello-world-war.git"
            }
        }
        stage ('Build') { 
             steps {
                echo "QA"
             }
        }
        stage ('Deploy') { 
             steps {
                echo "QA"
             }
        }
      }           
 }
