node{
	Stage('SCM Checkout')
		{ git 'https://github.com/AjayThakurHCL/hellogitworld' }

	Stage('Compile Package')
	Def MavenHome = tool name: 'maven', type: 'maven'
	
	"${MavenHome}/bin/mvn package
	//{ mvn package }
	
	//Stage('Email Notification')
	
	//{ mvn package }
}
