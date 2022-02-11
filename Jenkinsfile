pipeline {
  agent any
  stages {
    stage('Construcao') {
      steps {
        echo 'construcao'
      }
    }

    stage('Teste') {
      parallel {
        stage('Teste') {
          steps {
            echo 'testando'
          }
        }

        stage('Firexox') {
          steps {
            echo 'firefox'
          }
        }

        stage('Edge') {
          steps {
            echo 'edge'
          }
        }

      }
    }

    stage('Final') {
      steps {
        echo 'programa executando'
      }
    }

  }
}