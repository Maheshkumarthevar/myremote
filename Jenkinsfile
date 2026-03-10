pipeline{
agent any
stages
stage('checkout'){
 step{
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
reportName:'MY HTML PIPE PAGE'
])
}
}
}
}
