# monitoring-prom-grafana
#For running prometheus

docker run -p 9090:9090 -v C:\Users\skarv\Downloads\monitoring\monitoring\src\main\resources\prometheus.yml:/etc/prometheus.yml prom/prometheus:latest --config.file=/etc/prometheus.yml

#For running grafana

docker run -p 3000:3000 grafana/grafana:latest
