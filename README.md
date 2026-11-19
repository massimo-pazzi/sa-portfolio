# Портфолио системного аналитика — Максим Поципух

> Все материалы обезличены: названия заказчиков и систем, API-пути, поля и идентификаторы заменены. Схемы перерисованы с нуля.

## Об авторе

Максим Поципух — фулл-стек системный аналитик.

**Опыт:** пришел в системный анализ из B2B-продаж enterprise ИТ-решений: соединяю глубокое понимание потребностей бизнеса с навыками описания процессов, проектирования ИС и интеграций (BPMN, UML, REST API, C4, ERD).

**Домены: видеосервисы и подписочные платформы · корпоративное обучение (EdTech) · ЖКХ и эксплуатация недвижимости (PropTech).**

Telegram: [@maxim_potsipukh](https://t.me/maxim_potsipukh)

## Матрица компетенций

| Компетенция | Артефакт | Кейс |
|---|---|---|
| Бизнес- и функциональные требования | [Бизнес-требования и функциональные требования к видеоконтуру](case-1-video-contour/requirements/01-requirements.md) <br> [Требования к цифровому двойнику ЖКХ Москвы](case-3-housing-digital-twin/requirements/01-requirements.md) | [1](case-1-video-contour/README.md) <br> [3](case-3-housing-digital-twin/README.md) |
| User Stories | [Пользовательские требования к видеоконтуру ](case-1-video-contour/requirements/05-user-stories.md) <br> [Пользовательские требования к цифровому двойнику](case-3-housing-digital-twin/requirements/01-requirements.md#user-stories) | [1](case-1-video-contour/README.md) <br> [3](case-3-housing-digital-twin/README.md) |
| Use Cases | [Сценарии взаимодействия видеоконтура](case-1-video-contour/requirements/06-use-cases.md) <br> [Прогноз и назначение работы](case-3-housing-digital-twin/requirements/01-requirements.md#uc-1-рассмотреть-прогноз-и-назначить-работу) | [1](case-1-video-contour/README.md) <br> [3](case-3-housing-digital-twin/README.md) |
| ER-диаграммы | [ER-модель видеоконтура](case-1-video-contour/data/README.md) <br> [Модель данных цифрового двойника ЖКХ Москвы](case-3-housing-digital-twin/data/README.md) | [1](case-1-video-contour/README.md) <br> [3](case-3-housing-digital-twin/README.md) |
| Нефункциональные требования | [НФТ видеоконтура](case-1-video-contour/requirements/02-nfr-load.md) <br> [НФТ тренажера](case-2-emotion-trainer/README.md#нефункциональные-требования) | [1](case-1-video-contour/README.md) <br> [2](case-2-emotion-trainer/README.md) |
| Безопасность | [Модель угроз, безопасность и сохранность видеоконтура](case-1-video-contour/requirements/03-security.md) | [1](case-1-video-contour/README.md) |
| Наблюдаемость | [ТЗ на фичу видеоконтура: метрики, алерты, логи, приемка](case-1-video-contour/requirements/04-observability.md) | [1](case-1-video-contour/README.md) |
| BPMN | [Бизнес-процесс прохождения тренажера эмоций](case-2-emotion-trainer/bpmn/trainer.png) | [2](case-2-emotion-trainer/README.md) |
| UML | [Sequence загрузки и нарезки](case-1-video-contour/diagrams/sequence-upload.png) · [Sequence просмотра с переподписью](case-1-video-contour/diagrams/sequence-playback.png) · [State задачи нарезки](case-1-video-contour/diagrams/transcode-job-states.png) <br> [Sequence курса и LMS](case-2-emotion-trainer/diagrams/sequence-scorm.png) <br> [Sequence решения инженера](case-3-housing-digital-twin/diagrams/sequence-prevention.png) | [1](case-1-video-contour/README.md) <br> [2](case-2-emotion-trainer/README.md) <br> [3](case-3-housing-digital-twin/README.md) |
| Архитектура | [Контейнеры видеоконтура (C4)](case-1-video-contour/diagrams/containers.png) <br> [Варианты архитектуры тренажера эмоций](case-2-emotion-trainer/README.md#варианты-архитектуры) | [1](case-1-video-contour/README.md) <br> [2](case-2-emotion-trainer/README.md) |
| API и интеграции | [API: маршрут плейлистов HLS видеоконтура](case-1-video-contour/api/README.md) <br> [контракт данных SCORM с LMS](case-2-emotion-trainer/README.md#контракт-данных-с-lms) <br> [Потоки и качество данных ЖКХ](case-3-housing-digital-twin/requirements/02-data-and-integration.md) | [1](case-1-video-contour/README.md) <br> [2](case-2-emotion-trainer/README.md) <br> [3](case-3-housing-digital-twin/README.md) |
| Тестирование требований | [Тест-кейсы видеоконтура](case-1-video-contour/tests/test-cases.md) · [Трассировка BR → FR → TC видеоконтура](case-1-video-contour/tests/traceability.md) <br> [Приёмка и трассировка ЖКХ](case-3-housing-digital-twin/tests/acceptance.md) | [1](case-1-video-contour/README.md) <br> [3](case-3-housing-digital-twin/README.md) |
| Право | [Правовой режим тренажера эмоций: дерево решений по 152-ФЗ](case-2-emotion-trainer/README.md#правовой-режим-дерево-решений-по-ст-11-152-фз) | [1](case-1-video-contour/README.md) |

## Кейсы системного анализа

| # | Кейс | Тип | Роль | Ключевые артефакты |
|---|---|---|---|---|
| 1 | [Видеоконтур платформы монетизации кулинарного контента](case-1-video-contour/README.md) | учебно-практический проект «Су-Шеф», в проде без внешних пользователей | все роли: продукт, анализ, архитектура, разработка, тестирование, эксплуатация | требования, нагрузка и емкость, модель угроз, ТЗ на наблюдаемость, C4, UML, OpenAPI, тест-кейсы |
| 2 | [AI-тренажер эмоций для сотрудников магазинов](case-2-emotion-trainer/README.md) | реальный пресейл, федеральный ритейлер | системный анализ, архитектура решения, 152-ФЗ | BPMN, UML, контракт SCORM, НФТ, варианты архитектуры, дерево решений |
| 3 | [Цифровой двойник ЖКХ Москвы](case-3-housing-digital-twin/README.md) | реальный предпроект по запросу Мосстратегии | концепция, требования, постановка прогноза, метрики и прототип | BR/FR, User Stories, Use Cases, ER, sequence, потоки данных, приемка |

## Другие кейсы: бизнес-анализ, продукт, данные

Опубликованы отдельными репозиториями. В них меньше системного анализа и больше экономики, рынка и продукта.

| Кейс | Тип | Роль |
|---|---|---|
| [Окупаемость ИИ-фильтра заявок для грузовой авиакомпании](https://massimo-pazzi.github.io/b2b-value-case/) | коммерческий проект, система внедрена | бизнес-анализ, экономика решения |
| [ИИ-консультант по вину для сети супермаркетов](https://massimo-pazzi.github.io/wine-ai-case/) | реальный пресейл | продукт, категорийная экономика |
| [ИИ-ассистент для сети быстрого питания](https://massimo-pazzi.github.io/fastfood-assistant-case/) | реальный тендер | продукт, метрики, оценка нагрузки |
| [Гостиничный рынок Петербурга](https://massimo-pazzi.github.io/hotel-market-case/) | исследование на открытых данных | аналитика данных, прогноз |
| [Доклад на РМЭФ-2026](https://massimo-pazzi.github.io/rief-2026-talk/) | выступление | докладчик |

## Порядок чтения

1. **[Матрица компетенций](#матрица-компетенций)** — найти нужную компетенцию и сразу открыть артефакт. Если время ограничено, этого достаточно.
2. **README кейса** — контекст, заинтересованные стороны, ограничения, ключевые решения. 5–10 минут на кейс.
3. **Артефакты кейса** — в порядке, который указан в разделе «Содержание» внутри кейса: от требований к процессам, данным, API и проверке.

## Структура репозитория

```text
README.md                         обзор портфолио и матрица компетенций
case-1-video-contour/
  README.md                       кейс проектирования видеоконтура
  requirements/
    01-requirements.md            бизнес- и функциональные требования, доступ
    02-nfr-load.md                профиль нагрузки, расчёты и НФТ
    03-security.md                модель угроз и сохранность видео
    04-observability.md           метрики, алерты и приёмка наблюдаемости
    05-user-stories.md            пользовательские истории и критерии приёмки
    06-use-cases.md               основные и альтернативные сценарии
  data/
    README.md                     ER-модель, связи и правила целостности
    er-model.png                  изображение для страницы модели
  diagrams/                       C4, UML sequence/state и ER
  api/
    README.md                     описание контрактов доставки видео
    openapi.yaml                  спецификация маршрута HLS-плейлистов
  tests/
    test-cases.md                 сценарии приёмки
    traceability.md               трассировка BR → FR → TC
case-2-emotion-trainer/
  README.md                       кейс проектирования AI-тренажера эмоций
  bpmn/                           процесс: trainer.bpmn + SVG/PNG
  diagrams/                       UML sequence/state, дерево решений по 152-ФЗ
case-3-housing-digital-twin/
  README.md                       концепция цифрового двойника жилого фонда
  requirements/                   требования, сценарии, обмен данными и метрики
  data/                           логическая модель и правила целостности
  diagrams/                       ER и UML sequence: исходники, SVG/PNG
  tests/                          сценарии приёмки и трассировка
LICENSE                           условия использования материалов
```

В `diagrams/` рядом с изображениями SVG/PNG лежат редактируемые исходники `.mmd` или `.drawio`.


## Контакты

Telegram: [@maxim_potsipukh](https://t.me/maxim_potsipukh)

## Лицензия

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ru) для текстов и диаграмм, MIT для кода и SQL. Подробно в [LICENSE](https://github.com/massimo-pazzi/sa-portfolio/blob/main/LICENSE).
