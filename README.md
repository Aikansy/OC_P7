# GROUPIX - Groupomania internal social network

_In order to run this project, you will need a database using **mysql** (for sequelize) and create a **named database**._
_To access the history, you can go to_ [OC_P7_groupomania](https://github.com/Aikansy/OC_P7_groupomania) [^1]

Stacks

    > normalize.css
    > react
    > react-dom
    > react-router-dom
    > yarn

    > bcrypt
    > cors
    > dotenv
    > express
    > helmet
    > jsonwebtoken
    > multer
    > mysql2
    > nodemon
    > path
    > sequelize

## CLONE THE PROJECT

```
git clone https://github.com/Aikansy/OC_P7
```

## BACK-END PROCESS

### Install dependencies

_(terminall) Go to **OC_P7/back** folder, then..._

```
npm install
```

### Create needed file(s)

_Create **config.env** file in **OC_P7/back/config/** with in it:_

```
PORT=<the desired port for the back-end server except 3000>
DB_NAME=<named database>
DB_USER=<DB user name>
DB_PASSWORD=<DB password>
DB_HOST="localhost"
RANDOM_TOKEN_SECRET=<your secret string>
ROLE_TOKEN=<element to include in the password during registration to allocate the admin role>
```

### Start the back-end server

_(terminall) Return to **OC_P7/back** folder, then_

```
nodemon server
```

## FRONT-END PROCESS

### Install dependencies

_go to **OC_P7/front** folder_

```
npm install
```

### Start the front-end server

_go to **OC_P7/front folder**_

```
yarn start
```

or

```
npm start
```

[^1]: GitHub didn't take filename changes into account so the initial project (and its history) was moved to another repository.
