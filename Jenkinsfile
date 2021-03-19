node ('maven'){
    stage ('Checkout'){
    echo " cloning the repo "
    git credentialsId: 'Youarecool!', url: 'https://github.com/.git'
}
stage ('runningScript'){
    echo " running the script"
    echo " running the script over and over " 
    sh "sh test.sh"
    
}
    stage('Final') {
     echo " The job is completed " 
    }
    
}
