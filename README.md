# nodejscafe
A full-working restaurant application, using nodejs and MySql and Express


1- Package installation
2- .Env file content
//Server
PORT = 8080

//Connection
DB_PORT = 3306
DB_HOST = localhost
DB_USERNAME = root
DB_PASSWORD = password
DB_NAME = cafenodejs

ACCESS+TOKEN = token

3- How to generate token
in terminal type node
then
require('crypto').randomBytes(64).toString('hex')
