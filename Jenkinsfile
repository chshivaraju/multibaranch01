node('master')
    {
   
    stage('continuous delivery') 
         {
         git 'https://github.com/sunildevops77/maven.git'
          }
  
    stage('continuous build') 
         {
            sh 'mvn package'
          }

}

