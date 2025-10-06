![](http://images.restapi.co.za/pvt/Noroff-64.png)
# Back-end Development Year 1
 
NOTE: Remember to create the .env file with the information for your database. The username, password, database and host information needs to be in the .env file.

**Example .env:**
```sh
ADMIN_USERNAME=your-username
ADMIN_PASSWORD=your-password
DATABASE_NAME=guitardb
DIALECT=mysql
DIALECTMODEL=mysql2
DB_PORT=3306
PORT=3000
HOST=localhost
TOKEN_SECRET=your-token-secret
```


### Bruno REST collection
A Bruno collection is located in the `/bruno` folder. Please use the `POST Login` request to set a valid `accessToken` (using a post-request script) to be used for protected routes. 