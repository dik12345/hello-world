pipeline {
    agent any 
    tools {
 tool name: 'apache maven', type: 'maven'       
}  
stages  {
    stage('build') {
        steps {
        sh 'mvn clean package'
        }
    }
} 
    
}

