     pipeline {
        agent any
        stages {
         
          stage("build & sonarqube") {
            agent any
            steps {
              withSonarQubeEnv('Sonarqube') {
              #  sh 'mvn clean package sonar:sonar'
              }
            }
          }
        }
      }
