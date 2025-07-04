# Awesome SLO  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Ниже вы увидите тщательно отобранный список ресурсов, по тематике измерения надежности и производительности с [SLI/SLO](https://sre.google/sre-book/service-level-objectives/).  
Релевантные теме инструменты, доклады, статьи, заметки.

Мы вдохновлялись [awesome-sre](https://github.com/dastergon/awesome-sre)

**Что такое SLI/SLO и SLA?**
> **Service Level** – уровень обслуживания (SL)  
> * **SLI (Indicator)** – конкретная измеряемая метрика, которая показывает, насколько хорошо предоставляется услуга. Например: Доступность (99,9% времени сервис доступен) или Время отклика (95% запросов обрабатываются за 200 мс)  
> * **SLO (Objective)** - цель уровня обслуживания, значение SLI, которое вы обещаете поддерживать.  Например: "Наш сервис должен быть доступен 99,95% времени в месяц" или "95% запросов должны обрабатываться быстрее 300 мс"
> * **SLA (Agreement)** — договор с клиентом, где SLO превращаются в гарантии с штрафами за нарушения
>   
> ***SLO** — это внутреннее соглашение, которое помогает командам понимать, какие показатели критичны для пользователей*

## Участие в дополнении списка

Пожалуйста, сначала ознакомьтесь с [правилами внесения предложений](CONTRIBUTING.md). ❤️ Мы ценим вклад каждого участника!

## Список рескрсов по категориям

### Инструменты SLO
* [Sloth-Next](https://github.com/ALLSLO-COMMUNITY/sloth-next) - форк Sloth.dev развиваемый сообществом ALLSLO. Генератор правил вычисления SLI и правил алертов SLO для AlertManger, UI Grafana. поддержка Prometheus и VectoriaMetrics
* [Sloth.dev](https://sloth.dev/) - генератор правил вычисления SLI и правил алертов SLO для AlertManger, UI Grafana. поддержка Prometheus и VectoriaMetrics
* [Pyrra.dev](https://github.com/pyrra-dev/pyrra) - средство вычисления и отслеживания SLI/SLI, свое UI, только Prometheus
* [Google SLO Generator](https://github.com/google/slo-generator) - вычислитель SLI/SLO, получает данные из внешних источников и вычисления сохраняет также во вне
* [SLO Calculator](https://slc.alexewerlof.com/) - интерактивный инструмент для изучения поведения SLI/SLO
* [OpenSLO](https://www.nobl9.com/community/openslo) - спецификация SLI/SLO инструментонезвисимая, разарбатывается Nobl9

### Жизненный цикл SLO
* [SLODLC](https://www.slodlc.com/) - метоодология Service Level Objective Development Lifecycle, разработана Nobl9

### Особеснности вычисления SLI/SLO
* Презентация "[Part 2: Service Level Objective (SLO) Math](https://hpe-developer-portal.s3.amazonaws.com/Part+2_Running+Reliable+systems_SLO+Math.pdf)" (2022) - проблемы вичисления SLI
* Видео "Математика SLO..." (RndTech Reliability Meetup 2, 2025) [RuTube](https://rutube.ru/video/af628e467852ddb365b11ae3b0ed964d/), [YouTube](https://www.youtube.com/watch?v=PhM5-U52fBE) — сложности в вичислении SLI
* Видео "SLI/SLO/SLA в микросервисном приложении" (HighLoad, 2024) [VkVideo](https://vkvideo.ru/video-152308462_456239797), [YouTube](https://youtu.be/h0aZ_QNMTxU)- особесности SLI для микросервисов
* Статья "[Rules backfilling via vmalert](https://victoriametrics.com/blog/rules-replay/)" (VictoriaMetrics Blog, 2023) - как пересчитать SLO по историческим метрикам за интервал в прошлом в VictoriaMetrics
* Статья *[Composite SLO](https://blog.alexewerlof.com/p/composite-slo) (2023) - о расчете сложно-составных SLO

### Внедрение SLO
* Видео "SLOмано все. Короткая история о борьбе с реальностью" (2025) [VkVideo](https://vk.com/video-179458361_456239083), [YouTube](https://www.youtube.com/watch?v=1QmTSIhhljs) - о проблемах внедрения SLO и их решении на примере компаний Сбермаркет и Купер
* Статья "[Как внедрить SLO в продукт и получить от этого пользу](https://habr.com/ru/companies/skbkontur/articles/739774/)" (Habr, 2023)  - о проблемах внедрения SLO и их решении на примере компании [Контур](https://kontur.ru/)

### Телеграм каналы и группы об SLI/SLO
* [Группа ALLSLO](https://t.me/allslo_ru) - открытая группа рускоговорящего сообщества по SLI/SLO
* Канал [The Last of 9th](https://t.me/r9yo11yp9e) - о поддержании, измерении надежности, SLI/SLO и практиках SRE
