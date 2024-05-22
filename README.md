### Hexlet tests and linter status:
[![Actions Status](https://github.com/maximus335/devops-for-programmers-project-74/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/maximus335/devops-for-programmers-project-74/actions)

### Build github action status:
[![Actions Status](https://github.com/maximus335/devops-for-programmers-project-74/actions/workflows/push.yml/badge.svg)](https://github.com/maximus335/devops-for-programmers-project-74/actions)

## Описание
Для работы потребуется `docker`, `docker-compose`. Для запуска используется `Makefile`, необходимо установить `make`. Никакие другие зависимости не требуются, вся работа происходит внутри контейнеров.

## Команды запуска
- `make compose-test` - запуск тестов локально, под капотом используется файл `docker-compose.yml`
- `make compose-run` - запуск приложения локально, под капотом используются оба файла - `docker-compose.yml` и `docker-compose.override.yml`

## Dockerhub
Образ сборки лежит по пути `maximus335/devops-for-programmers-project-74:latest`.
