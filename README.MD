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
![WhatsApp Image 2020-04-09 at 3 10 41 PM](https://user-images.githubusercontent.com/57304597/82052778-34942a00-968a-11ea-929b-f5b6fa7483fb.jpeg)
![WhatsApp Image 2020-04-09 at 3 16 35 PM](https://user-images.githubusercontent.com/57304597/82052791-39f17480-968a-11ea-842b-81d5319b532d.jpeg)
![WhatsApp Image 2020-04-09 at 3 23 12 PM (1)](https://user-images.githubusercontent.com/57304597/82052815-4249af80-968a-11ea-99ef-77b6b0bdb17d.jpeg)
![WhatsApp Image 2020-04-09 at 3 23 12 PM](https://user-images.githubusercontent.com/57304597/82052837-48d82700-968a-11ea-8529-1dd94e8a174c.jpeg)
