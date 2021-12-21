pipeline {
    agent any
    stages {
        stage ('Git clone') {
            steps {
                dir (sample-repo) {
                  git url: "https://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@github.com/Anand1294/sample-repo2"
                }
                dir (sample-repo2) {
                    git url:"${url}", branch: "main"
                }
            }
        }
            
    }
}
