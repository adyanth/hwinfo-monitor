# hwinfo-monitor
Grafana+Prometheus on docker-compose for HWinfo Remote Sensor Monitor

[Here](https://github.com/adyanth/hwinfo-exporter) is the source for the hwinfo-exporter.

You can run this by cloning this repo and compose up.

```
git clone https://github.com/adyanth/hwinfo-exporter.git
cd hwinfo-exporter
docker-compose up -d
```

Open `http://localhost:3000` for grafana and `http://localhost:9090` for prometheus.
