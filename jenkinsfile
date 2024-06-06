pipeline
{
    agent any
    stages
    {
        stage('checkout')
        {
git 'https://github.com/kartikeya-1112/mytesting'
        }
        stage('build')
        {
            sh 'mvn compile'
        }
    }
}