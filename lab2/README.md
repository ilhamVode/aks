# Task 2 — Loki + Zabbix + Grafana

| Файл | Что внутри |
| --- | --- |
| `Отчет.md` | Отчёт: логирование, мониторинг, визуализация, запросы и ответы на вопросы |
| `Отчет.pdf` | Тот же отчёт в PDF, с титульным листом |
| `data/docker-compose.yml` | Стек: Nextcloud, Loki, Promtail, Grafana, Postgres, Zabbix server и web |
| `data/promtail_config.yml` | Сбор логов Nextcloud в Loki (`job=nextcloud_logs`) |
| `data/template.yml` | Шаблон Zabbix: ping Nextcloud через `status.php` |
| `data/screenshots/` | Скриншоты хода работы (контейнеры, логи, Zabbix, Grafana) |
