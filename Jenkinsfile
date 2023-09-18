pipeline {
           agent {
                label "built-in"
           }
         stages {
                 steps ('deploy-index') {
                        sh "cp -r index.html /var/www/html"
                        sh "chmod -r 777 /var/www/html"
                 }
         }
}
