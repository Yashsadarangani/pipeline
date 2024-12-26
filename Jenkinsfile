node{
  stage('Build'){
    echo "Building"
  }
  stage("test"){
    echo "Testing"
  }
  if (currentBuild.currentResult=="SUCCESS"){
    echo "Went Well"
  }else{
    echo "Failed"
  }
}
