pipeline
{
 agent any
stages
 {
stage ('Package')
{
steps
 {
      withMaven (maven: 'MAVEN-HOME')
{
bat 'mvn package'
}
}
}
}
}
