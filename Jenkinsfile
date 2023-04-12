pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                // 
              sh "echo 'my first build' >> haseeb"
            }
        }
        stage('Test') { 
            steps {
                // 
              echo "Test completed successfully"
            }
        }
        stage('Deploy') { 
            steps {
                sh 
                '''
                ls -lah
                whoami
                pwd
                '''
                // 
             // sh "scp -r -i /var/jenkins_home/.ssh/id_rsa -o 'StrictHostKeyChecking no' /var/jenkins_home/workspace/Test/* root@172.17.0.4:~/"
            }
        }
    }
}
