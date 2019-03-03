node ('maven'){
    stage ('Checkout'){
    echo " cloning the repo "
    git credentialsId: 'NAWAB786', url: 'https://github.com/MNadir786/SaturdayRepeat.git'
}
stage ('runningScript'){
    echo " running the script"
    sh "sh test.sh"
}
}
