#!/usr/bin/env groovy 
node('master') {
	try {
	     stage('build')
	      {
	      	sh "echo 'we8 are building'"
		}
	     stage('test')
	     { 
	     	sh "echo 'we are testing'"
		}
	     stage('deploy')
	     {
	     	sh "echo 'we11 are deploying'"
		}

		catch(error)
		{
		throw error 
		}
		finally {
		}
		}
		}

