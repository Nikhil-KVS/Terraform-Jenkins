node {
    stage('git clone') {
        git branch: 'main', url: 'https://github.com/Nikhil-KVS/Terraform-Jenkins.git'
    }
    stage('tf init') {
        bat 'terraform init'
    }
    stage('tf plan') {
        bat 'terraform plan'
    }
}
