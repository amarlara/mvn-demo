pipeline{
  stages{
    stage("Build"){
      steps{
        shell('mvn clean install')
      }
    }
  }
  post{
    always{
      cleanws()
    }
  }
}
