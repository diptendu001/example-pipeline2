pipeline {
    agent any
    stages {
       stage('Compile code ')
        {
          steps {
                  javac HelloWorld.java
                }
        }
       stage('Run code ')
        {
          steps {
                  java HelloWorld
                }
        }
    }
}

