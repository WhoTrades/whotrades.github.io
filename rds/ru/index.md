---
layout: default
title: Release Deployment Service
description: Сервис управления релизами
---

1. [Что такое RDS](#что-такое-rds)
1. [А есть демо?](#а-есть-демо)


### Что такое RDS

Это простой сервис управления релизами. 

На текущий момент он умеет: 
- Собирать релиз (build)
- Распространять собранный релиз по серверам (install)
- Активировать релиз (в том числе откатываться на предыдущие версии)
- Выполнять миграции баз данных
- Хранить и отображать лог сборки
- Пересоздавать конфигурации cron (*)
- Автоматически делать релизы для связанных проектов при релизе основного
- Назначать для каждого проекта свой агент сборки релиза
- Распространять локальные конфигурации проектов по серверам
- Блокировать сборку релиза для проекта

(*) - на данный момент не реализовано распространение хранимой конфигурации cron по серверам

### А есть демо?

Конечно есть. Вам понадобится docker и примерно полчаса времени.
[Вот инструкция](demo.html)