# Quickstart

For the moment the installation can be a bit tedious, sorry for that

## Production
⚠️ The project is still in beta use with caution

In this example the project is built and deployed on a docker  and/or on a local node environement

### Setup the back

**Clone the back**

`git clone https://github.com/datatlas-erasme/back.git`

`git checkout dev`

** Setup your `.env` file **

```
DATATLAS_BACK_END_PORT=3000
NOTION_API_KEY=YOUR_NOTION_API_KEY
BEARER_TOKEN=YOUR_BEARER_TOKEN

```

**Using Docker Compose**

`docker-compose up`

**Using npm**

` npm install && npm run dev`

-----

The back is now available on **`mydomain.com:3000`**


### Setup the front

**Clone the front**

`git clone https://github.com/datatlas-erasme/front.git`

`git checkout dev`

** Setup your `.env` file **

Should point on the back server

```
REACT_APP_BACKEND_URL='http://`back.mydomain.com:3000`
```


**Using Docker Compose**

`docker-compose up`

**Using npm**

` npm install && npm run dev`

-----

The front is now available on **`front.mydomain.com:3000`**


### Init instance conf
By default 
