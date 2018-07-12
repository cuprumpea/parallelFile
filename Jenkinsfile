pipeline {
  agent any
  stages {
    stage('jianchu') {
      parallel {
        stage('jianchu') {
          steps {
            echo 'jianchu'
          }
        }
        stage('bingxing jianchu') {
          steps {
            echo 'bingxingjianchu'
          }
        }
        stage('bingxingjianchu2') {
          steps {
            echo 'bingxingjianchu2'
          }
        }
        stage('bingxingjianchu3') {
          steps {
            echo 'bingxingjianchu3'
          }
        }
      }
    }
    stage('goujian') {
      parallel {
        stage('goujian') {
          steps {
            echo 'goujian'
          }
        }
        stage('bingxinggoujian1') {
          steps {
            echo 'bingxinggoujian1'
          }
        }
      }
    }
  }
}