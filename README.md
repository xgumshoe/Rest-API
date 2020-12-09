# Rest-API
Rest-API


GET http://localhost:3000/subscribers/

###

GET http://localhost:3000/subscribers/:id

###

POST http://localhost:3000/subscribers 
```
Content-Type: application/json
{
"name": "Amazing Person", "subscribedToChannel": "REST API Test"
}
```
###

DELETE http://localhost:3000/subscribers/:id

###

PATCH http://localhost:3000/subscribers/:id
```
Content-Type: application/json 
{
"name": "New Nam"
}
```
