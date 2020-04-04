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
     sh 'pm2 list'
     sh 'ng serve --host 0.0.0.0 --port 4201'

 }
