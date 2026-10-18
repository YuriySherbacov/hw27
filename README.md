# Monitoring Stack (Prometheus + Grafana + Alertmanager)

## Опис
Docker-стек моніторингу з Node Exporter, Grafana дашбордами та алертами в Telegram.

## Запуск
```bash
docker compose up -d

Сервіси

Сервіс Порт URL
Prometheus 9090 http://localhost:9090 
Grafana 3000 http://localhost:3000 
Alertmanager 9093 http://localhost:9093

Grafana: admin / 12061995Time21
Дашборди Grafana

Node Exporter Full — ID 1860
Docker / cAdvisor — ID 193

Алерти

DiskSpaceLow — вільне місце < 15%
HighCPUUsage — CPU > 80%
TargetDown — таргет недоступний