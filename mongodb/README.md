# MongoDB

### Container creation.
In this container you can install an instance of MongoDB, for this you need to do the following steps:

1. Download docker and install in your PC. You can see this URL:<br>
   <https://docs.docker.com/engine/install/>
2. Enter the directory where this file is located and execute:<br>
   `docker-composer up` or `docker-composer up -d` "If you want to enable the daemon 😈".
3. You can click in this route <http://localhost:27017> and check if the MongoDB server is enabled.
   You can see the following message:<br>
   "It looks like you are trying to access MongoDB over HTTP on the native driver port."

### Data connection.
The data connection to the server are:

* __Server:__ localhost
* __Port:__ 27017
* __User:__ root "You can change this in the `MONGO_INITDB_ROOT_USERNAME` environment"
* __Pass:__ 123 "You can change this in the `MONGO_INITDB_ROOT_PASSWORD` environment"

 
__NOTE__. If you need to add a new feature, you can edit the __docker-compose-yml__.