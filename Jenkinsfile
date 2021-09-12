node {

    stage('check tools') {
        sh "node -v"
        sh "npm -v"
    }

    stage('checkout') {
        //checkout scm
    }

    stage('npm install') {
        sh "sudo npm install"
    }

    stage('run app') {
        sh "sudo npm start"
    }
    stage('unit tests') {
        //sh "sudo npm test -- --watch=false"
    }

    stage('protractor tests') {
        //sh "sudo npm run e2e"
    }
}