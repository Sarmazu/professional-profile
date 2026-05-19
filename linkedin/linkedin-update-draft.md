# LinkedIn Update Draft

Черновик блоков для ручного переноса в LinkedIn.

Основано на `ai-readable-professional-profile.md`, `target-roles.md` и role-specific резюме из `resumes/`.

## Headline

Основной вариант:

Technical Program Manager | Infrastructure & Platform Transformation | CI/CD, Kubernetes, OpenStack, DevOps / Platform Engineering

Более платформенный вариант:

Internal Developer Platform Lead | Platform Engineering | CI/CD, DevOps Platform, Developer Productivity, Kubernetes

AI-adjacent вариант:

AI Infrastructure Program Manager | Platform / Infrastructure TPM | AgentOps, External Memory, Self-hosted AI Lab

## About

Technical / Infrastructure Program Manager с фокусом на infrastructure & platform transformation, CI/CD и delivery-программы в mission critical IT-среде.

Управляю сложными техническими изменениями на стыке инфраструктуры, platform engineering, DevOps, архитектуры, эксплуатации и продуктовых команд: migration programs, production readiness, cutover, risk management, capacity planning, delivery lifecycle, cross-functional coordination.

Работал с платформенным контуром масштаба 3000+ VM, 15+ Kubernetes-кластеров, 100+ микросервисов, 30-40 релизов в квартал, 100 000 RPS суммарной нагрузки и mission critical level.

Ключевые кейсы: миграция mission-critical платформы с VMware/RHEL на OpenStack/AstraLinux, миграция CI/CD и delivery-конвейера на новый технологический стек, запуск выделенной DevOps-команды как внутреннего платформенного сервиса, построение onboarding-функции для систем-потребителей, управление infrastructure lifecycle и capacity planning.

Отдельно развиваю self-hosted AI-agent lab как личный инженерный проект: Git-backed Markdown external memory, Basic Memory/MCP semantic discovery layer, OpenClaw agent runtime, AgentOps policy, LLM chat ingestion pipeline with SQLite FTS5 и supporting Docker/Linux infrastructure. Это pet-lab / actively evolving prototype, а не production enterprise AI platform.

Целевые направления: Technical Program Manager, Infrastructure / Platform Transformation, Internal Developer Platform Lead, Platform Engineering Manager, AI Infrastructure Program Manager.

## Experience: Innotech, current role

### Platform Infrastructure & DevOps Lead / Руководитель инфраструктуры и DevOps стрима

Август 2025 — настоящее время

Отвечаю за инфраструктурное направление и развитие delivery-конвейера, DevSecOps. Инфраструктура по полному жизненному циклу: планирование и бюджетирование под потребности проектов, рост нагрузки, изменение архитектуры и требований, участие в согласовании в проект, проработка архитектурных решений, контроль выполнения паттернов надежности и доступности систем, получение инфраструктуры, развертывание и настройка системного и прикладного ПО, передача в эксплуатацию.

Курирую DevOps-команду: приоритизация задач, планирование спринтов и кварталов, контроль качества исполнения, эскалации, управление ключевыми проектами и изменениями. Управляю сквозными CI/CD и инфраструктурными изменениями от требований и оценки до передачи в эксплуатацию.

Масштаб:
- стрим 90+ человек;
- 6 команд: 4 продуктовых, 1 DevOps и 1 onboarding;
- 3000+ VM;
- 15+ Kubernetes-кластеров;
- 100+ микросервисов;
- 30-40 релизов в квартал;
- 100 000 RPS суммарной нагрузки;
- mission critical level.

Ключевые результаты:
- Выстроил управляемую infrastructure и DevOps/delivery-функцию платформы.
- Разработал каталог типовых sizing-компонентов платформы под нагрузку и внедрил его в операционные процессы.
- Разработал стандарт инженерных практик разработки микросервисных компонентов: sizing, параметры отказоустойчивости, соответствие стратегиям деплоя.
- Разработал сквозной процесс изменения инфраструктуры с зонами ответственности архитекторов, менеджеров, команд разработки и сопровождения.
- Оптимизировал инфраструктуру, повысив метрику эффективности утилизации с 83% до 99%.
- Около 30% инфраструктуры описали в IaC и стали применять для крупного setup.
- Оптимизировал CPU actual usage кластеров Kubernetes НТ и prod с 15% до 80%.
- Убрал проблему незапланированности или нехватки инфраструктуры как класс, количество VM выросло с 2000 до 3000+.

## Experience: Innotech, previous role

### Team Lead / Integration Services Lead → DevOps Team Lead

Апрель 2022 — Август 2025

Сначала лидировал команду интеграционных сервисов: управлял потоком типовых и нетиповых интеграций, SLA, обращениями, консультациями, документацией и эскалациями. Затем руководил DevOps-командой платформы, с которой создавали производственный процесс, поставки, CI/CD и инфраструктурные изменения.

Ключевые программы:

Миграция mission-critical платформы с VMware/RHEL на OpenStack/AstraLinux
- Отвечал за планирование и сроки, декомпозицию миграции по подсистемам, координацию продуктовых команд, аналитиков, тестирования, сопровождения и инфраструктурных подразделений.
- Управлял рисками производительности, эскалациями и готовностью сред к cutover.
- Миграция пользовательской нагрузки выполнена в срок за 6 месяцев вместо исходной оценки 9 месяцев.
- Работы выполнены без аварий 1-2 категории.
- Развернуто и сконфигурировано 1500+ VM на новом стеке.
- Проведено 6 нагрузочных тестов СУБД.

Миграция CI/CD и delivery-конвейера на новый технологический стек
- Отвечал за план миграции, сроки, декомпозицию этапов, управление рисками, постановку задач DevOps-инженерам и продуктовым командам, контроль готовности MVP, обучение команд и передачу процесса в сопровождение.
- План выполнен в 6-месячный срок.
- Реализованы необходимые CI/CD-функции с минимальным влиянием на релизный процесс: 1 простой 3 дня.
- Мигрировал 6 команд.
- На первом этапе мигрировали 4 магистральных пайплайна.
- Старый стек полностью выведен из эксплуатации.
- Миграция не повлияла на сроки проектных релизов команд.

Запуск выделенной DevOps-команды и внутреннего платформенного сервиса
- Сформировал выделенную DevOps-команду из инженеров, ранее распределенных по продуктовым командам, без провала текущего delivery.
- Выстроил сервисную модель для продуктовых команд.
- Унифицировал CI/CD-практики, повысил взаимозаменяемость инженеров и снизил трудоемкость релизных операций.
- Запуск команды выполнен за 1 квартал.
- Снижение аварийности тестовых сред в 2 раза.
- Снижение трудоемкости production update на 20%.
- Ускорение релизного процесса на тестовых средах на 50%.
- Многообразие компонентов и конфигураций уместили в 4 магистральных пайплайна.

Построение onboarding-функции систем-потребителей платформы
- Управлял кросс-функциональной командой 8 человек.
- Команда обрабатывала 20-40 интеграций в неделю.
- 95% заявок обрабатывались в срок при сохранении численности команды.
- Снижено в 2 раза число аварий по интеграциям в prod при росте потока изменений.
- Типовые интеграции полностью вынесены из зоны ядровой команды платформы.

## Experience: Galamart

### Руководитель департамента управления данными и web-сервисов / Head of Internal Systems Development

Ноябрь 2020 — Апрель 2022

Руководил департаментом системной разработки. Управлял несколькими кросс-функциональными командами, техническими лидерами, портфелем проектов и внутренними бизнес-системами. Взаимодействовал с бизнес-заказчиками по приоритетам портфеля и сдаче поставок. Отвечал за стабильность систем, аварии и удовлетворенность бизнеса.

Ключевые результаты:
- Стабилизировал работу департамента после ухода ключевого лидера, разделил большую команду на управляемые продуктовые направления, выстроил приоритизацию и процессы delivery.
- Выделил четыре команды по продуктам: ESB, EDW, BI, WebServices с назначением технических лидеров.
- Внедрил infrastructure и engineering-практики: self-hosted/AWS, IaC, CI/CD, Git flow, DBVC.
- Снизилось число аварий на web-сервисах примерно в 3 раза за полгода.
- Организовал перевод BI/QlikView на данные КХД, запустил слой проверок DQ, организовал миграцию управленческой отчетности на EDW.
- Ускорил подготовку витрин на 4 часа и сместил готовность отчетности на дату -1 в начало рабочего дня.
- Запустил важные для бизнеса web-сервисы: автозаказ товаров в магазин, конструктор коммерческих технологий управления ценами сети, управление сезонами, монитор движения товаров от РЦ до магазина.

### Руководитель проектов

Июнь 2020 — Ноябрь 2020

Управлял проектами разработки внутренних web-сервисов для бизнес-функций: сбор требований, приоритизация с бизнесом, управление разработкой, ожиданиями, сроками, приемкой и внедрением.

## Experience: Informsvyaz Service

### Менеджер проекта

Март 2018 — Май 2020

Проектное управление в IIoT: средний уровень — железо, верхний уровень — frontend, backend. Разработка серверного программного обеспечения, web, электроники, системная интеграция, проектирование. Сводил воедино требования заказчика, технические и ресурсные ограничения, интересы бизнеса и команду для получения результата. Сочетал гибкие методологии и классический проектный подход.

Ключевые результаты:
- Разработал структурированный ассортимент, каталог продукции и специализированные материалы для продвижения, развил стратегическую концепцию продукта.
- Внедрил стандарты операционной деятельности и бизнес-процессов: разработки, версионности, документирования по ЕСКД, планирования.
- Разработал структуру отдела, описал бизнес-процессы, развил коммуникации.
- Инициировал разработку новой архитектуры программной части комплекса, определил ее функционал и особенности, конкурентные преимущества, сформулировал долгосрочный план, инициировал набор команды.
- Внедрил элементы проектного управления в разработке железа, ПО, интеграции.
- Провел сертификацию продукции, в том числе метрологическую, внесение в реестр российского ПО.

## Project: Self-hosted AI-agent lab

Personal engineering project / self-hosted lab / actively evolving prototype.

Designed and operate a self-hosted AI-agent lab platform combining Git-backed Markdown external memory, Basic Memory/MCP semantic discovery layer, OpenClaw agent runtime, AgentOps policies, LLM chat ingestion pipeline with SQLite FTS5, and supporting Docker/Linux home-lab infrastructure.

Ключевые компоненты:
- MemVault as Git-backed Markdown external memory;
- Basic Memory/MCP as semantic discovery layer;
- OpenClaw as self-hosted agent runtime;
- PetOps as designed / partially implemented operational agent model;
- MemOps as designed / partially implemented chat interface for knowledge operations;
- llmchat converter with SQLite FTS5;
- OMV/Docker/Linux supporting infrastructure.

Важно: это не production enterprise AI platform, не commercial AI product, не enterprise RAG platform, не production MLOps и не stable multi-agent production system.

## Skills

Priority skills:

Technical Program Management; Infrastructure Transformation; Platform Engineering; DevOps; CI/CD; Kubernetes; VM Infrastructure; Private Cloud; OpenStack; AstraLinux; Capacity Planning; Production Readiness; Cutover Planning; Release Management; Risk Management; Cross-functional Coordination; Stakeholder Management; Internal Developer Platform; Developer Productivity; Engineering Productivity; Quality Gates; Onboarding; Teamleading.

AI-adjacent skills:

AI Infrastructure; AgentOps; Agentic Systems; External Memory; Semantic Retrieval; MCP; Git-backed Knowledge Base; Markdown-first Knowledge Architecture; Self-hosted Infrastructure; Docker/Linux Operations; LLM Chat Ingestion; SQLite FTS5.

## Education and courses

Уральский федеральный университет имени первого Президента России Б.Н. Ельцина, Екатеринбург

Высшая школа экономики и менеджмента, Финансы и кредит

2011

Courses:
- Взлет Т1: из эксперта IT в лидеры команд, Т1 Цифровая академия, Teamlead, 2024.
- Luxoft training, Администрирование Jira, 2021.
- НПО Сапфир, PostgreSQL dev-1, 2021.
- GeekBrains от Mail.ru Group, HTML/CSS. Интерактивный курс, 2020.
- НОУ ДПО «Урало-Сибирский центр развития персонала «Фабрика управляющих проектами», интенсивная подготовка к сертификации по международному стандарту управления проектами IPMA, 2019.

## Safety checklist before publishing

- Не добавлять телефон, email, дату рождения, Telegram.
- Не добавлять IP, токены, конфиги, внутренние названия закрытых систем.
- Не описывать AI pet-lab как production enterprise AI platform.
- Не заявлять hands-on software engineering там, где источники описывают management / lead / coordination.
- Не добавлять новые достижения, которых нет в исходном портфолио.
- Не удалять доменные бренды, относящиеся к обучению, например `GeekBrains от Mail.ru Group`.
