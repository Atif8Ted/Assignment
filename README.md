# Dipper

In this project playing with setTimeout, setInterval, clearTimeout and clear Interval




## Install Dependencies
Open terminal 


and type following command
```sh 
$ cd <directory>

npm install
npm run server
``` 


please check this urls on Postman.


- open http://127.0.0.1:8000/

- initiate request http://localhost:8000/api/request?connId=19&timeout=8000

- check running request status http://localhost:8000/api/serverStatus

this is put request

- kill the connection http://localhost:8000/api/kill

body {
	"connId": 19
}

# curl Request

```
curl "http://localhost:8000/api/request?connId=19&timeout=8000"
```
