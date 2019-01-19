node {
    stage('build'){
        echo "building"
    }
}
node {
    stage('test'){
        echo "testing"
    }
}
stage('Get approval'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying"
    }
    
    stage('Deployement completion')
    {
        input "Deployment completion"
    }
    node {
        
        stage('job is deployed')
        echo "Deployement completed"
    }
}
