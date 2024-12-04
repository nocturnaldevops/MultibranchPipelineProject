pipeline
{
  agent any
  stages
  {
    stage("Cont_download")
    {
      steps
      {
        git branch: 'feature2', url: 'https://github.com/nocturnaldevops/MultibranchPipelineProject.git'
      }
    }
    stage("Contbuild")
    {
      steps
      {
        sh 'mvn package' 
      }
    }
  }
}
