pipeline {
    agent any

    parameters {
        booleanParam(defaultValue: true, description: '', name: 'userFlag')
        string(defaultValue: 'DC', description: '', name: 'name')
        choice(choices: 'Batman\nFlash\nGreenlanthern', description:'' , name: 'your DC hero')
    }

    stages {
        stage("foo") {
            steps {
                echo "flag: ${params.userFlag}"
            }
        }
    }
}
