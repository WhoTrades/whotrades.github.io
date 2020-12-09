---
layout: default
title: Release Deployment Service
description: Демонстрация
---

### Требования
- [Docker Engine](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Git](https://git-scm.com/downloads) (опционально)

### Установка

Скачайте конфигурацию для Docker Compose: 
```bash
git clone https://github.com/WhoTrades/rds-demo.git
```
или [как архив из списка релизов](https://github.com/WhoTrades/rds-demo/releases)

Откройте терминал (Linux/Mac) или командную строку (Windows), перейдите в папку /путь/к/rds-demo/rds и запустите docxker-compose: 
```bash
cd /path/to/rds-demo/rds
docker-compose up
```

Веб интерфейс RDS будет доступен по адресу: [localhost:8080](http://localhost:8080)

Демо-проект будет доступен по адресу: [localhost:8000](http://localhost:8000) 
(до выкладывания демо-проекта на сервер через RDS будет отображаться ошибка 404)