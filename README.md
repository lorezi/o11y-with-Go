# o11y with Go

### Note
Add Prometheus metrics to your micro-services.

Prometheus is deployed as a HTTP server alongside the applications


### Usage

```bash
# Terminal 1
$ go run main.go


# Terminal 2
$ curl http://127.0.0.1:8080/metrics

# Terminal 3
$ docker run --rm -it -p 9090:9090 prom/prometheus:v2.36.2
```


