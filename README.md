# Django Prometheus

Docker-composed django and prometheus services

```
docker-compose up
```

http://localhost:9090/graph

http://localhost:9090/graph?g0.range_input=1h&g0.stacked=1&g0.expr=django_http_requests_total_by_method_total&g0.tab=0

https://docs.timescale.com/latest/tutorials/tutorial-howto-monitor-django-prometheus

https://github.com/korfuri/django-prometheus