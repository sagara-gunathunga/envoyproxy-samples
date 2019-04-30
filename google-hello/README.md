Envoy proxy route traffic to Apache2 server on host
=

In this sample Envoy proxy route traffic to  Apache2 server on host

1. Start Apache2 server on host
```
sudo apachectl start
```

2. Run the proxy using Docker compose
```
docker-compose up
```

3. Test the sample
```
Service  : curl http://localhost:8080/
```

