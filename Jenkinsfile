pipeline{
    agent none
    stages {
        stage ("CodeStage"){
            agent {
                label 'Java-slave'
            }
            steps {
                echo "First pipeline"
            }
        }
    }
}
