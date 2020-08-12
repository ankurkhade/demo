node{

    stage('SCM Checkout')
    {
         url: 'https://github.com/ankurkhade/demo.git'
    }
    
    stage('Run Docker Compose File')
    {
        sh 'sudo docker-compose build'
        sh 'sudo docker-compose up -d'
    }
}
