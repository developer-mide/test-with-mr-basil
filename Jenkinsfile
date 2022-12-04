pipeline{
    agent any
    stages{   
      stage("fetch from Github"){
         steps{
            git branch: "vp-rem", url: "https://github.com/developer-mide/vprofile-project.git"
         }
         post{
            success{
                echo "Fetched from Github successfully"
            }
            failure{
                echo "Unable to fetch from Github"
            }
          }
       }
   }
}

