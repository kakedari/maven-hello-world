node{
    properties(
        [
            parameters(
                [string(defaultValue: 'Hello', name: 'Greeting')]
            )
        ]
    )  
 
    stage('Hello') {
      
        echo "Hello"
      
    }
    stage('Example') {
           
                echo "${parameters.Greeting} World!"
            
        }
  
}
