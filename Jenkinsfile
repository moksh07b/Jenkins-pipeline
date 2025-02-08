pipeline{
agent any
stages{
stage("Code"){
  steps{
sh "npm install --verbose -omit=optional"
sh "npm run build"
}
}
}
}
