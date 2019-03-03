node ('maven'){
    stage ('Checkout'){
    echo " cloning the repo "
    git credentialsId: 'NAWAB786', url: 'https://github.com/MNadir786/SaturdayRepeat.git'
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
