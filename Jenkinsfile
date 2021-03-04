pipeline{
agent any 
stages{
stage("git checkout"){
steps{
git "https://www.github.com/ksksaikiran/java"
}
}
stage("test"){
steps{
sh "mvn test"
}
}
}
}
