pipeline {
  agent any
  parameters {
        string(name: 'Greeting', defaultValue: 'Hello', description: 'How should I greet the world?')
    }
  stages {
    stage('Hello') {
      steps {
        echo "Hello"
      }
    }
    stage('Example') {
            steps {
                echo "${params.Greeting} World!"
            }
        }
  }
}
