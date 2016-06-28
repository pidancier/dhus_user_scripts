# DHuS User Scripts
Scripts to read/update user entities.

## HowTo use

### Set the environment variables that configure the DHuS:

+ **DHOST** DHuS Host address eg: localhost:8080, scihub.copernicus.eu/dhus/
+ **DLOGIN** DHuS login username to connect to the $DHOST DHuS
+ **DPASS** DHuS login password to connect to the $DHOST DHuS

### Use a command:

Parameters between angle brackets (chevrons) are mandatory.

Parameters between brackets ([]) are optional.

Get users
```./getUsers [username]```

Update a User:  
```./updateUser <username> [Options...]```

Available options are:
* -D_PHONE=<phone number>
* -D_ADDRESS=<address>
* -D_PASSWORD=<password>

