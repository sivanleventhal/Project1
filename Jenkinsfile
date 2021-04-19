node {
    stage("clone"){
        git branch: 'main', url: 'https://github.com/sivanleventhal/Project1.git'
    }
    stage("myapp"){
        bat "python myapp.py"
    }
}
