# Chat Server using C
Chat Server developed using socket programming in C 

## For Compiling:
$ gcc Server.c -o server -lpthread
$ gcc Client.c -o client -lpthread

## For Starting Client and Server:
./Server
./Client

## For Login To Server:
login [alias] 
Here [alias] is optional, if it is not mentioned, the name will be set as Anonymous.
The name can be changed by the command:

alias [new_name] After this, you alias will be changed to the new name you have given.
To send a message to everyone connected at the moment:

## For Sending Messages:
send [message]
To send a message to a specific alias:

## Private Messaging:
whisp [user_alias] [message] If the target alias is not active at that moment, message will not be sent anywhere
You can disconnect from the server by typing:

## Logout:
logout You can again reconnect by using the login command
You can terminate the client by typing:

## Termination Command:
exit
