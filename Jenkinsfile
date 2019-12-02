node('ANSIBLE') {
    
    stage('GIT') {
        git 'https://github.com/mobeenajakeer04/roles.git'
    }
    
    stage('DEPLOY') {
        sh 'ansible-playbook -i inventory usetomcatrole.yml'
    }
}
