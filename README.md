# jenkins


## Declarative Pipeline fundamentals

In Declarative Pipeline syntax, the pipeline block defines all the work done throughout your entire Pipeline.

### Jenkinsfile (Declarative Pipeline)

```

pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                // 
            }
        }
        stage('Test') { 
            steps {
                // 
            }
        }
        stage('Deploy') { 
            steps {
                // 
            }
        }
    }
}

```

- Execute this Pipeline or any of its stages, on any available agent.
- Defines the "Build" stage.
- Perform some steps related to the "Build" stage.
- Defines the "Test" stage.
- Perform some steps related to the "Test" stage.
- Defines the "Deploy" stage.
- Perform some steps related to the "Deploy" stage.
