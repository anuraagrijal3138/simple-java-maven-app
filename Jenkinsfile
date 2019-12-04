pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
            echo 'Hello World'
         }
      }
      stage('Kubectl Check') {
         steps {
            sh 'kubectl get nodes -o wide'
         }
      }
   }
}
