# redis-grafana

Monitor redis instance with Grafana, Prometheus and Redis exporter

Start with:
```
docker-compose up -d
```

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

Have fun and play with alerts, notifications etc.

Grafana notifications to Slack: https://medium.com/@_oleksii_/grafana-alerting-and-slack-notifications-3affe9d5f688


Note:

If you want to monitor your own Redis instance just remove provided one from focker-compose and setup yours in prometheus.yml