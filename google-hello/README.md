Envoy proxy route traffic to Google
=

In this sample Envoy proxy route traffic to Google

Run the proxy using 'docker run'
```
docker run --rm -p 80:10000 -p 8080:9901 -v $(pwd)/envoy.yaml:/etc/envoy/envoy.yaml envoyproxy/envoy:latest
```
Run the proxy using Docker compose
```
docker-compose up
```

How to test the sample
```
Service  : curl http://localhost/
Admin UI : curl http://localhost:8080
```

