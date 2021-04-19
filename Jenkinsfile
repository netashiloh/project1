properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage ("clone") {
         git 'https://github.com/netashiloh/project1.git'
        }
        stage ("run script") {
            bat 'python myapp.py'
        }
 }
