# Домашнее задание к занятию 3 «Использование Ansible»

## Структура проекта

```
.
├── group_vars
│   └── prod
│       └── vars.yml
├── inventory
│   └── prod.yml
├── README.md
├── site.yml
└── templates
    ├── clickhouse.conf.j2
    ├── lighthouse.conf.j2
    └── vector.yml.j2
```

## Назначение

Данный плейбук осуществляет установку и настройку для работы между собой трех сервисов: Clickhouse, Lighthouse и Vector.

## Переменные

|Переменная| Описание|
|-------|-------|
|clickhouse_version| Версия пакетов Clickhouse|
|clickhouse_packages| Необходимые для установки пакеты Clickhouse|
|vector_version| Версия пакета Vector|
|clickhouse_ip| Динамическая переменная IP адреса хостовой машины Clickhouse|

## Теги

08-ansible-03-yandex
