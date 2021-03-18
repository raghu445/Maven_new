node('master') 
{
    stage('ContinuousDownload_test')
    {
       git 'https://github.com/intelliqittrainings/maven.git'
    }
    stage('ContinuousBuild_test')
    {
       sh 'mvn package'
    }
    
}
