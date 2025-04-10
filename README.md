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

## 3. Run The Application 
1. Run ``npx next dev`` which use `` http://localhost:3000`` to access the web application
2. Run ``http://localhost:15672`` on your browser to run RabbitMQ management tools. username is ``guest`` and password also ``guest``

## 3. Test Application
1. import ``ORDER-APP-BE.postman_collection.json`` which already in the source repo
2. you can view the order processed data using this page ``http://localhost:3000/api/orders/list``

## 4. Things Need To Be Added In The Future
1. Test each functioanlity using mock testing 
2. Implements ``Mongoose`` as models
3. Use repository pattern as a wrapper class for a model processing to ensure code standardization and managing exceptions 
4. Use enumerations to standard exceptions message as it could be reuse in any routes 


   

