pipeline{
agent any
stages('checkout'){
stage{
echo 'cheking out repo'
git'https://github.com/Maheshkumarthevar/myremote'
}
}
stage('publish'){
steps{
 publishHTML([
sllowmissing:true,
alwaysLinktoLastBuild:false,
keepAll:false,
reportDir:'.',
reportFiles:'Index.html',
reportName:'MY HTMLPIPE PAGE'
])
}
}
}
}
