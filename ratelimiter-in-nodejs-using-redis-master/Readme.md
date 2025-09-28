## Ratelimiter in NodeJS using Redis

This rate limiter in nodejs using redis. you can use this to ratelimiter in your application to rate limit the apis.

### Install dependencies

```bash
npm install
```

### Run Server

```bash
node index.js
```


### Rest API for for calling the GET API

```bash
curl --location 'http://localhost:7005/ping' \
--header 'user_id: 111112' 
```
