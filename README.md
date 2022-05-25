# GROUPIX - Groupomania internal social network

_In order to run this project, you will need a database using **mysql** (for sequelize) and create a **named database**._

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
