pipeline{
     agent any
     stages{
         stage('checkout') {
            steps{
              git branch : 'main',url:
'git@github.com:raj-cmd971/skill_lab_devops.git'
            }
     }
     stage ('hello'){
        steps{
      echo "hello from jenkins pipelines!"
    }
 }
      stage("good bye"){
     steps{
    echo "jenkins finished successfully"
           }
         }
       }

