node {
    stage('Postman api test') {
        echo 'Api test'       
        bat 'npm install'
        bat 'newman run https://api.postman.com/collections/8463341-a56184fa-d6d2-4788-b862-fc545a8f2725?access_key=PMAT-01HQJSGSS9CW8C4769G60JC4G9 -r cli,htmlextra'
    }
}
