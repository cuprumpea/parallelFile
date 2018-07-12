pipeline {
  agent any
  stages {
    stage('检出') {
      parallel {
        stage('检出') {
          steps {
            echo '检出'
          }
        }
        stage('并行任务之检出') {
          steps {
            echo '并行任务之检出'
          }
        }
        stage('并行任务2之检出') {
          steps {
            echo '并行任务2之检出'
          }
        }
        stage('并行任务3之检出') {
          steps {
            echo '并行任务3之检出'
          }
        }
      }
    }
    stage('构建') {
      parallel {
        stage('构建') {
          steps {
            echo '构建'
          }
        }
        stage('并行任务1之构建') {
          steps {
            echo '并行任务1之构建'
          }
        }
      }
    }
  }
}
