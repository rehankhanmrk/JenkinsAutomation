node {
    
	

	
	stage('Git') {
		git 'https://github.com/gustavoapolinario/node-todo-frontend'
	}
	stage('Build') {
		sh 'npm install'
	}
	stage('Test') {
		sh 'npm test'
	}
	stage('startnode') {
		sh 'npm start'
	}
	
    
}
