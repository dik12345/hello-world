pipeline {
    agent any 
      tools {
  maven 'apache maven3'
}
stages  {
    stage('build') {
        steps {
        sh 'mvn clean package'
        }
    }
} 
    
}

