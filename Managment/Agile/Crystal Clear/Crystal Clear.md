В 1991 году Алистер Кокбёрн, один из соавторов [[Agile манифест разработки программного обеспечения]], задался целью создать эффективную методологию разработки ПО. Для этого он опросил множество проектных команд и изучил их кейсы разработки.

[[Ключевые правила Crystal]]

#### 3 основные метода концепции:

1. **быстрая доставка полезного кода**, переход от больших и редких развёртываний кода к меньшим и более частым релизам [[Метод маленьких партий]].
2. **усовершенствование через рефлексию** — получение сведений о том, что работало хорошо и плохо в предыдущей версии программы для улучшения следующей версии ПО (как ретроспектива, но для продукта).
3. **осмотическая коммуникация** — Алистер объяснил восприятие и обмен информацией между разработчиками приложения в одной комнате как фоновый шум, напоминающий явления осмоса.

#### Самая простая из возможных классификаций Crystal — по критерию количества людей в проекте:

- **Clear** — от 2 до 8 человек, которые сидят вместе в одном или смежных офисах
- **Yellow** — 10-20 человек
- **Orange** — 20-50 человек в команде
- **Red** — от 50 до 100.

Для масштабных проектов используют дополнительные цвета: **Maroon, Blue** и **Violet**.

## Цикличный процесс Crystal Clear

#### Большинство проектов по Crystal Clear состоит из 6 циклов, которые определяют список обязанностей и задач проектной команды:

1. **Проектный цикл** — хоть проект сам по себе — единица продукта, за ним обычно следует другой проект, повторяющий цикл. Проектный цикл состоит из трёх частей: **подготовка** (сбор команды, исследование на 360°, определение методологии), серия из двух и более **циклов доставки** и «**ритуала завершения**». Длится от нескольких дней до недель.
2. **Цикл доставки** — состоит из повторной **калибровки плана** выпуска ПО, серий из одной или нескольких **итераций**, в результате которых создаётся **протестированный интегрированный код**, **доставки** реальным **пользователям** и «**ритуала завершения**». Длительность — от 1 недели до 3 месяцев.
3. **Итерация** — состоит из трёх больших частей: **итерационное планирование**, дневная и интеграционная **деятельность цикла** и «**ритуал завершения**» проекта.
4. **Рабочая неделя/день** — выбор дня или недели в виде **единицы времени цикла** зависит от формата проекта и команды. Например, в таком формате проводятся еженедельные встречи отделов, отчётные встречи тимлидеров, «brown-bag» семинары (когда каждый приносит собственный ланч и за перекусом решаются вопросы по проекту).
5. **Период интеграции** — разработка, интеграция и тестирование системы. В некоторых командах процесс сборки-тестирования проходит не прекращаясь, за что отвечает отдельная машина, другие идут по пути интеграции раз в день или три раза в неделю. **Чем короче цикл интеграции, тем лучше.** Длительность от 30 минут до 3 дней (зависимо от опыта команды).
6. **Разработка** — написание и проверка части кода. Это по сути основа работы программиста в «гибкой разработке». Член команды берёт небольшую задачу, **программирует решение (в идеале с тестированием)** и проверяет её в конфигурации с целой системой. Занимает от 15 минут до нескольких дней.