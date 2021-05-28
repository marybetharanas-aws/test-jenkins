pipeline{
  agent any
  options{
    copyArtifactPermission('test-6800-artifact');
  }
  stages{
    stage("Make artifact"){
      steps{
        sh "echo 'Hello, world!' > artifact.txt"
      }
    }
  }
}
