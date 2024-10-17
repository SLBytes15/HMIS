## HMIS

### Step - 1 Setup
- npm init
- npm packages: express mongoose bcrypt jsonwebtoken validator firebase dotenv
- making folder in src folder 
    - [dbConnection](./src/db/dbConnection.js)
    - [controller](./src/controller/)
    - [models ](./src/models)
    - [routes](./src/routes)
    - [utils](./src/utils/)
    - files : {[app.js](./src/app.js) ,[index.js](./src/index.j`)}
- dotenv [env file](./.env)
- mongodb connection [dbConnection](./src/db/dbConnection.js)
- listen in [index.js](./src/index.j`)

### Step - 2 Models
- creating [userSchema](./src/models/user.models.js`)
- building user details


### Step - 3 Controllers
- creating functionality for user like register, login and logout functions [user.controller](./src/controller/user.controllers.js)
- setup register user 
    - input user details, email, password for authenticatoin
    - hashing the password
    - providing access token
- setup login user 
    - input email and password
    - check for email or id exist 
    - check for password and comparing password for validation
    - check for valid access token
-setup logout user 
    - delete access token

### Step - 4 Routes
- import router from express
- setup routes for each {post} user function: register, login and logout

### Step - 5 utils
- API error handling

### Step - # HMIS
