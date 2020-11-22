# KeyStore
This is a Rest service, running in an internal server, Jetty, through TCP and UDP.

To start the app you should run the MultiThreadServer, then run the UDP and TCP clients. 

You can see the list of commands you can use below:

 -> {"command": put, "key": person, "payload": {"name": Filipe, "age": 23}}
 -> {"command": get, "key": person}
 -> {"command": remove, "key": person}
 -> {"command": update, "key": person, "payload": {"name": Machado}}
 -> {"command": getAll}
 
 You can acess the Store in http://localhost:8081/api/store/messages/ and I've used the Postman client to test the webservice.


