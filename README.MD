![WhatsApp Image 2020-04-09 at 1 33 43 PM](https://user-images.githubusercontent.com/57304597/82047626-1c6bdd00-9681-11ea-89fd-7e7e9f8d5f19.jpeg)

## Docker + React App + API Express + MySQL

This project implements a quick start up project using the facebook`s create-react-app as the app front end,
a configured express API server connected to a MySQL database (easy to change) and optionally the phpMyAdmin
preconfigured as the database admin. And even better, all stack works as Docker containers.

After install Docker, run the following code to setup the development or production stack:

````
$ npm install -g create-react-app  

$ docker-compose up
````

And that`s all, in the docker-compose.yml file its possible to change the enabled ports, database password, dev/production envoroments and other simple configs, change it as you need.


To rebuild and run:

```
docker-compose down && docker-compose build && docker-compose up -d
```

