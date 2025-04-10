This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/create-next-app).

## 1. Getting Started

First, run install below application:
1. Mongodb
2. Rabbit MQ
3. NodeJS : Version 22
4. NPM : Version 11.2.0

## 2. Setup Database

Create schema name ``order-app``

Create below collections
1. ``consumers``
2. ``orders``
3. ``settings``


## 3. Setup Application

1. Copy ``.env.example`` and rename ``.env``
2. Update all the information in the ``.env``
3. Execute ``run npm install`` to install ``node_modules`` libraries

## 3. Run the Application 
1. Run ``npx next dev`` which use `` http://localhost:3000`` to access the web application
2. Run ``http://localhost:15672`` on your browser to run RabbitMQ management tools. username is ``guest`` and password also ``guest``

## 3. Test Application
1. import ``ORDER-APP-BE.postman_collection.json`` which already in the source repo


   

