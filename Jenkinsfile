pipeline {
  agent any
 stages {
   stage ('Code checkout') {
     steps {
       git 'https://github.com/Dileep232/New-repo.git'
     }
   }
   stage ('Deploy to nginx') {
     steps {
       sh 'cp -f /var/lib/jenkins/workspace/nginx/index.html /usr/share/nginx/html/index.html'
     }
   }
 }
}  
