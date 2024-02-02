# pysatellite-json-server

### RUN
```sh
$ npx json-server --watch db.json --port 3001
```

### Docker
```sh
$ docker build -t jserver:0.0.2 .
$ docker run -dit --name json-server-2 -p 8051:80 jserver:0.0.2
```

### Deploy
- https://fly.io/docs/hands-on/install-flyctl/
- fly auth login
-
