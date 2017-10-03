node {
   stage 'Stage 1'
   		echo 'Hello World 1'
   stage 'Build'
   		sh 'mvn package -f tibco.bwce.sample.palette.http.RequestResponse.application/ -Dproperty.file=docker-dev.properties'
}