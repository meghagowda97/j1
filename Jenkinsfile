pipeline {
    agent any

    stages {
        stage('git checkout') {
            steps {
               git clone https://github.com/meghagowda97/j1.git
            }
        }
        stage('create a directory') {
            steps {
               'sh mkdir /home/ubuntu/change'
            }
        }
        stage('rename a direcory') {
            steps {
                sh 'mv change renamed'
      
            }
        }
    }
}
