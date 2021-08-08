# Backend-End Challenge
![alt tag](https://static.wixstatic.com/media/7f8adc_d803ec63e9e443a288209456ce076e0f~mv2.png/v1/fill/w_132,h_26,al_c,q_85,usm_0.66_1.00_0.01/ChatClass_logo.webp)

ChatClass Back-End challange API implementation. There is a Postman collection and environment in docs folder. Import them in your Postman App to visualize the available endpoints.

## Technologies used to implement the API:

- [NodeJs];
- [KoaJs];
- [MongoDB];
- [Mongoose];
- [Jest];
- [Docker];

## Running the API with docker:

It is necessary to have [Docker] installed in your machine in order to run the following scripts:

To start the API:
```sh
docker-compose up
```
To stop the API:
```sh
docker-compose down
```

## Running the API without docker:

It is necessary to have configure a .env file containning the following varibales:
```
DB_URL=
APP_PORT=
```
To start the API:
```sh
npm start
```

## Running tests:

Tests are automatically runned by docker when using compose up, but they can be ran manually using the following command:
```
npm run tests
```
## Running the script to import Authors:

In order to run the import authors script, you need to execute the following command line:
```
node manage.js <path_to_your_csv_file>
```

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [NodeJs]: <https://nodejs.org/en/>
   [KoaJs]: <https://koajs.com/>
   [Mongoose]: <https://mongoosejs.com/>
   [MongoDB]: <https://www.mongodb.com/pt-br>
   [Jest]: <https://jestjs.io/pt-BR/>
   [Docker]: <https://www.docker.com/>

