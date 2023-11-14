  node {
    stages ("Cloning the repositery") {
         git branch: 'master', url: 'https://github.com/rajugajjela/git1.git' 
    }
    stages ('run the sample script') {
        sh './simple.sh'
    }
    stages ('Execute echo command') {
        echo "First scripted pipeline script"
    }
    
}
