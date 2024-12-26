node{
  stage('Build'){
    echo "Building"
  }
  stage("test"){
    echo "Testing"
  }
  if (currentBuild.result=="SUCCESS"){
    echo "Went Well"
  }else{
    echo "Failed"
  }
}
