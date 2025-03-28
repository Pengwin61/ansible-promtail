# Promtail

Устанавливает и настраивает Promtail на Debian-based Linux дистрибутивах.

Позволяет управлять конфигами promtail из git репозитория.
Скачивает конфиг из репозиторий сравнивает имя с `inventory_hostname`.

## Links:
* [github.com](https://github.com/grafana/loki)


## Variables:
* `promtail_exporter_version` (type=string, default="0.47.2") - Версия promtail