pipeline{
agent any
stages{
stage('python --version'){
agent{
docker {image 'python:latest'}
}
steps{
sh "pyrhon --version"
}
}
stage('groovysh --version'){
agent{
docker {image 'groovy:latest'}
}
steps{
sh "groovysh --version"
}
}
}
}
