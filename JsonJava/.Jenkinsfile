pipeline{
agent any
stages{
stage('Build')
{
steps{

bat "mvn compile"

}

}
stage('deploy')
{
steps{

echo 'displaying the code'
}
}
stage('testing')
{
steps{
bat "mvn compile"
}
}
stage('unit testing')
{
steps{
bat "mvn clean"
}
}
stage('release')
{
steps{
echo 'releasing the project'
}
}
}
}
