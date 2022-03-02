# MVC

auth0 functions as authentication as a service. 

auth0 is a tool, 0auth is a method

in '.env' you will need to push 'connection strings' to the 'auth_doman' section. This is where you will need to push the domain name to. Then client ID will need to go to the auth_client_id.

In the client folder under 'app' you will need to go into the Utils folder and then copy and paste the values under the export const variables like you did above. 

In 'connection_string' this is a connection to our database. 

In 'connection_string, your db id from mongo will be copied and pasted into the url string with the password as well. 

package.json brings in all the different services for your code. 

Schema is a tool that creates models for the db.

