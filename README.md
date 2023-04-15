This is a Springboot project build on Maven. You may use any suitable IDE to build and run the project by importing the Meddrones.zip file.

The H2 data schema contains 3 tables for medication, drones and loaded drones.
The URL for the H2 console is http://localhost:8080/h2-console (unless the port changes)
The credentials for the database are:

sa:
password: 

All 3 tables have preloaded data for drones and medication.

You can use Postman to test this API for the following methods:

http://localhost:8080/medication")  
	Get list of loaded Medication  
http://localhost:8080/drones")
	Get List of drones
http://localhost:8080/dronesToLoad")
	Get list of Available drones to load
http://localhost:8080/getLoadedDrone/{id}")
	Get information of loaded drone
http://localhost:8080/getWeightInDrone/{id}")
	Get current weight of medication in drone
http://localhost:8080/uploadFile")
	Upload medication image
http://localhost:8080/registerdrone",
	Register drone
http://localhost:8080/loadDrone",
	Load a drone with medication

Input should be in JSON format.
