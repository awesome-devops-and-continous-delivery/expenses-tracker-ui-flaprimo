# Espenses Tracker

### Apiary API
https://expensestracker.docs.apiary.io/

### Installation
In order to use this application you have to install dependencies first

```sh
npm install
```

### Run the application
In order to run this application you can execuite the following comand

```sh
npm start
```

If you want to start the application on a port different from 8080 (which is the default port) use the following command and choose the port you prefer.

```sh
npm start --expenses-tracker:port=8888
```


### How to build the docker image

```sh
docker build --rm --tag expenses-tracker /path/to/project
```


### How to run the docker image

```sh
docker run -p 8088:80 -it expenses-tracker # shows the logs direcly in the terminal


docker run -p 8088:80 -d expenses-tracker # should return the container_id
docker logs -f {container_id}
```
