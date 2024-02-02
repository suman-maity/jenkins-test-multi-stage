[Yesterday 6:08 PM] Satyajit P Chainy
//Boolean Flags

boolean runStage1 = true

boolean runStage2 = true
 
pipeline {

    agent any
 
    stages {

        stage('Stage 1') {

            when {

                expression {

                    return runStage1 // Only run this stage when 'runStage1' is true

                }

            }

            steps {

                // put whatever steps you need to execute here

                echo 'Executing Stage 1...'

             }

          }

          stage('Stage 2') {

            when {

                expression {

                    return runStage2 // Only run this stage when 'runStage2' is true

                }

            }

            steps {

                // put whatever steps you need to execute here

                echo 'Executing Stage 2...'

            }

        }

    }

}
