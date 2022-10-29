node{
 stage('downloading the source code')
    {
     git branch: 'main', url: 'https://github.com/nithyas0101/spring-petclinic.git'
    }
  stage('creating artifacts')
    {
      sh 'mvn package'
    }
  }