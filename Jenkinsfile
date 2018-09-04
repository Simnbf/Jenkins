// Simon 04/09/2018

node{
    stage("Init"){
        echo "SBF script initialising"
	}
	stage("Webservice"){
        def response = httpRequest 'http://localhost:8080/jenkins/api/json?pretty=true'
        println("Status: "+response.status)
        println("Content: "+response.content)   
    }
	stage("Ending"){
	    echo "Ending now see you later."
	}
}
