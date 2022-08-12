# github-usuario-
GET
/user/login
Name	Description
username *
string
(query)
The user name for login
username = carlos bonfatti

Name	Description 
password *
string
(query)
The password for login in clear text
password = pwd123

Curl
curl -X 'GET' \
  'https://petstore.swagger.io/v2/user/login?username=carlos%20bonfatti&password=pwd123' \
  -H 'accept: application/json'
Request URL
https://petstore.swagger.io/v2/user/login?username=carlos%20bonfatti&password=pwd123
Server response
Code	Details
200	
Response body
Download
{
  "code": 200,
  "type": "unknown",
  "message": "logged in user session:1660322855948"
}
POST
/user
Name	Description
body *
object
(body)
Created user object

Example Value
Model
{
  "id": 0,
  "username": "string",
  "firstName": "string",
  "lastName": "string",
  "email": "string",
  "password": "string",
  "phone": "string",
  "userStatus": 0
}
