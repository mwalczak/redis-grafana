# redis-grafana

Monitor redis instance with Grafana, Prometheus and Redis exporter

Login to Grafana:

http://localhost:3000

with: ```admin / secret``` (you can change password in docker-compose.yml)

Go to:

http://localhost:3000/dashboard/import

and import dashboard from file:
```
dashboard.json
```
The original dashboard was:
```
https://grafana.com/grafana/dashboards/763
```
Variable was removed as it blocked alerts usage.

gave fun and play with alerts, notifications etc.

