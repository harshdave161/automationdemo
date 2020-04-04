 node('yeahtesthai'){
        echo 'abhi new built gitlab si push krrha hai '
    stage('Cloning Git') {
        checkout scm
    }
        
    stage('Install dependencies') {
        nodejs('nodejs') {
            sh 'npm install'
            echo "Modules installed"
        }
        
    }
   sh 'pwd'
    echo 'yeah deko'
    sh 'pm2 list'
    // sh 'pm2 stop 3'
    // sh 'pm2 list'
    // sh 'pm2 start 3 "ng serve --host 0.0.0.0 --port 4201"'

 }
