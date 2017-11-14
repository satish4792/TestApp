@Library('MyPipelineLibrary@master')
import com.sap.ms.*
def log = new com.sap.ms.L()
log.info("Its my Pipeline")
node("swarm"){
	agent none
		stages {
			stage('Example'){
		steps{
				echo "Hello World."
				}
			}
		}
}
