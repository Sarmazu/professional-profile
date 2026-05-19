# AI Infrastructure Program Manager / AI Platform Program Manager

Резюме для hh.ru
Целевая роль: AI Infrastructure Program Manager / AI Platform Program Manager

Медведев Иван

Контакты: доступны в hh.ru / по запросу
Проживает: Екатеринбург / Белград
Готов работать удалённо, готов к редким командировкам

## Желаемая должность

AI Infrastructure Program Manager

## Специализации

AI Infrastructure Program Manager
AI Platform Program Manager
GenAI Infrastructure Program Manager
AgentOps / Internal AI Tools Lead

## Профессиональный профиль

Technical / Infrastructure Program Manager с сильным infrastructure/platform background и hands-on pet-lab опытом в AI infrastructure, AgentOps, external memory и agentic systems.

Основной профессиональный опыт — управление infrastructure/platform/delivery программами в mission critical IT-среде: infrastructure lifecycle, CI/CD migration, Kubernetes/VM-инфраструктура, platform engineering, production readiness, capacity planning, кросс-командная координация, управление рисками и зависимостями.

AI-направление развиваю через личный self-hosted lab: Git-backed external memory, Basic Memory/MCP semantic discovery layer, OpenClaw agent runtime, AgentOps policy, LLM chat ingestion pipeline with SQLite FTS5, MemOps, PetOps и supporting Docker/Linux infrastructure. Это не production enterprise AI platform, а практический инженерный контур для изучения AI infrastructure, agentic systems, external memory, semantic retrieval, MCP, agent runtime и AgentOps.

## Ключевые компетенции

AI Infrastructure; AgentOps; Agentic Systems; External Memory; Semantic Retrieval; MCP; Git-backed Knowledge Base; Markdown-first Knowledge Architecture; Self-hosted Infrastructure; Docker/Linux Operations; LLM Chat Ingestion; SQLite FTS5; Platform Engineering; Infrastructure Transformation; CI/CD; Kubernetes; VM Infrastructure; Technical Program Management; Cross-functional Coordination.

## AI / self-hosted pet-lab

2026

Owner / architect / operator pet-lab платформы

Личный инженерный проект для изучения AI infrastructure, agentic systems, external memory и self-hosted automation.

Спроектировал и развиваю self-hosted AI-agent платформу: Git-backed Markdown external memory, Basic Memory/MCP semantic retrieval, OpenClaw agent runtime, AgentOps policy, pipeline импорта LLM-диалогов с SQLite FTS5 и supporting Docker/Linux home-lab инфраструктуру.

Компоненты и масштаб:
- MemVault repo около 1.3 GB;
- 10 893 файлов в imports/llmchat;
- 15 daily notes;
- 35 entity notes;
- 21 record notes;
- 4 summaries;
- OpenClaw VM contour;
- OMV/home-lab host;
- Docker/nginx;
- Basic Memory/MCP layer;
- llmchat converter with SQLite FTS5;
- local STT contour;
- n8n/Nextcloud/home-lab как supporting infrastructure.

Ключевые решения:
- Спроектировал MemVault как Markdown-first external memory с Git source of truth.
- Ввел governance model: note types, templates, lifecycle import → daily → record → summary → entity.
- Интегрировал Basic Memory/MCP как semantic layer поверх Markdown corpus, не заменяя canonical storage.
- Развернул и описал OpenClaw self-hosted runtime с VM separation, workspace memory и handoff в MemVault.
- Спроектировал PetOps agent: Advisor + Executor, safe-read/safe-write/guarded-change/high-risk action classes.
- Адаптировал llmchat-knowledge-converter: Markdown normalization, SQLite FTS5, delta import, retrieval-ready corpus.
- Поднял supporting self-hosted infrastructure на OMV/Docker/nginx; подготовил n8n/Nextcloud как элементы automation/storage layer.
- Задокументировал local STT migration Whisper → GigaAM v3 ONNX как часть voice-to-agent interface.
- Спроектировал MemOps agent как чат-оператор базы знаний: поиск, фиксация заметок, нормализация записей, извлечение сущностей и передача устойчивых знаний в durable memory.
- Заложил модель изолированных agent workspaces: отдельные рабочие пространства, контексты, политики доступа и сценарии взаимодействия.
- Сформировал roadmap развития proactive agents: календарное планирование, напоминания, регулярная обработка знаний, контроль задач и извлечение полезных действий из накопленной базы через управляемую проактивность.

Результаты:
- Создан рабочий Git-backed knowledge corpus с governance, импортами, semantic layer и агентными правилами.
- MemVault стал canonical memory layer для личных знаний и LLM-диалогов.
- Basic Memory/MCP используется как semantic discovery layer.
- Подготовлена agent operations model для OpenClaw/PetOps.
- Создан retrieval/data-ingestion контур для LLM chat exports.
- Сформирована практическая база для дальнейшего career agent / AI-enabled knowledge workflow.
- MemOps выделен как основной чат-интерфейс к MemVault для поиска, записи, структурирования и нормализации знаний без прямой ручной работы с файлами.
- Сформирована концепция multi-agent workspace isolation: отдельные агенты и рабочие пространства для разных пользователей/друзей, с разделением контекста, данных и сценариев применения.
- Определен roadmap развития: self-hosted календаризация на базе Nextcloud/CalDAV, проактивные агентные сценарии, настройка частоты и границ инициативности агентов, регулярное извлечение полезных действий из накопленной базы знаний.

Ограничения:
- Проект не production и не enterprise deployment.
- Часть компонентов implemented, часть partially implemented/design.
- PetOps имеет policy/prompt/runbooks, но не подтвержден как стабильный production agent.
- Semantic search в converter частично in-progress.
- MemOps и изолированные workspaces описывать как designed/partially implemented, если нет подтвержденной стабильной эксплуатации.
- Календарный агент, Nextcloud/CalDAV-based planning и тонкая настройка проактивности — planned roadmap, не текущий результат.
- Не заявлять как production-ready personal assistant platform или multi-user agent platform без устойчивых ролей, политик доступа и рабочих сценариев.
- Не заявлять как production AI platform, enterprise RAG, commercial AI product, stable multi-agent production system, собственную разработку Basic Memory, production MLOps или fully automated career agent.

## Опыт работы

### Иннотех, Группа компаний

Информационные технологии, системная интеграция, разработка программного обеспечения.

#### Август 2025 — настоящее время

Platform Infrastructure & DevOps Lead / Руководитель инфраструктуры и DevOps стрима

Отвечаю за инфраструктурное направление и развитие delivery-конвейера, DevSecOps. Инфраструктура по полному жизненному циклу: планирование и бюджетирование под потребности проектов, рост нагрузки, изменение архитектуры и требований, участие в согласовании в проект, проработка архитектурных решений, контроль выполнения паттернов надежности и доступности систем, получение инфраструктуры, развертывание и настройка системного и прикладного ПО, передача в эксплуатацию.

Курирую DevOps-команду: приоритизация задач, планирование спринтов и кварталов, контроль качества исполнения, эскалации, управление ключевыми проектами и изменениями. Управляю сквозными CI/CD и инфраструктурными изменениями от требований и оценки до передачи в эксплуатацию.

Масштаб:
- стрим 90+ человек;
- 6 команд: 4 продуктовых, 1 DevOps и 1 онбординг;
- 3000+ виртуальных машин;
- 15+ кластеров Kubernetes;
- суммарная нагрузка 100 000 RPS;
- 100+ микросервисов;
- mission critical level;
- 30-40 релизов в квартал.

Результаты:
- Выстроил управляемую инфраструктурную и DevOps/delivery-функцию платформы: единая картина инфраструктуры, нормализация планирования мощностей, стандартизация инженерных практик, вовлечение сопровождения в развитие пайплайнов.
- Разработал каталог типовых sizing-компонентов платформы под нагрузку.
- Разработал стандарт инженерных практик разработки микросервисных компонентов: sizing, параметры отказоустойчивости, соответствие стратегиям деплоя.
- Оптимизировал инфраструктуру, повысив метрику эффективности утилизации с 83% до 99%.
- Около 30% инфраструктуры описали в IaC и стали применять для крупного setup, экономя время работ.
- Оптимизировал CPU actual usage кластеров Kubernetes НТ и prod с 15% до 80%.
- Убрал проблему незапланированности или нехватки инфраструктуры как класс, количество VM выросло с 2000 до 3000+.

#### Апрель 2022 — Август 2025

Team Lead / Integration Services Lead → DevOps Team Lead

Сначала лидировал команду интеграционных сервисов: управлял потоком типовых и нетиповых интеграций, SLA, обращениями, консультациями, документацией и эскалациями. Затем руководил DevOps-командой платформы, с которой создавали производственный процесс, поставки, CI/CD и инфраструктурные изменения.

Ключевые программы и проекты:

1. Миграция CI/CD и delivery-конвейера платформы на новый технологический стек

Отвечал за план миграции, сроки, декомпозицию этапов, управление рисками, постановку задач DevOps-инженерам и продуктовым командам, контроль готовности MVP, обучение команд и передачу процесса в сопровождение.

Результаты:
- Успешно выполнен план в 6-месячный срок.
- Реализованы все необходимые CI/CD-функции с минимальным влиянием на релизный процесс: 1 простой 3 дня.
- Мигрировал 6 команд.
- На первом этапе мигрировало 4 магистральных пайплайна.
- Старый стек полностью выведен из эксплуатации.
- Миграция не повлияла на сроки проектных релизов команд.

2. Запуск выделенной инженерной команды DevOps и построение внутреннего платформенного сервиса

Сформировал выделенную DevOps-команду из инженеров, ранее распределенных по продуктовым командам, без провала текущего delivery. Выстроил сервисную модель для продуктовых команд, унифицировал CI/CD-практики, повысил взаимозаменяемость инженеров и снизил трудоемкость релизных операций.

Результаты:
- Запуск команды за 1 квартал.
- Снижение аварийности тестовых сред в 2 раза.
- Снижение трудоемкости production update на 20%.
- Ускорение релизного процесса на тестовых средах на 50%.
- Многообразие компонентов и конфигураций уместили в 4 магистральных пайплайна.

3. Управление миграцией mission-critical платформы с VMware/RHEL на OpenStack/AstraLinux

Отвечал за планирование и сроки, декомпозицию миграции по подсистемам, координацию продуктовых команд, аналитиков, тестирования, сопровождения и инфраструктурных подразделений; управлял рисками производительности, эскалациями и готовностью сред к cutover.

Результаты:
- Миграция пользовательской нагрузки выполнена в срок за 6 месяцев вместо исходной оценки 9 месяцев.
- Работы выполнены без аварий 1-2 категории.
- Развернуто и сконфигурировано 1500+ VM на новом стеке.
- Проведено 6 нагрузочных тестов СУБД; для высоконагруженной части согласован bare metal, для остальной — повышенные IOPS на VM.

4. Построение функции онбординга систем-потребителей платформы

Управлял кросс-функциональной командой, отвечал за SLA по типовым интеграциям, обращениям и консультациям, приоритизировал backlog, распределял задачи между ролями, строил процессы обработки задач и обновления документации.

Результаты:
- Команда 8 человек обрабатывала 20-40 интеграций в неделю.
- 95% заявок обрабатывались в срок при сохранении численности команды.
- Снижено в 2 раза число аварий по интеграциям в prod при росте потока изменений.
- Автоматизированы процессы создания заявки по шаблону, создания файла конфигурации в конструкторе, валидации конфигураций при подготовке поставки.

### Франчайзинговая сеть Галамарт

Розничная торговля.

#### Ноябрь 2020 — Апрель 2022

Руководитель департамента управления данными и web-сервисов / Head of Internal Systems Development

Руководил департаментом системной разработки. Управлял несколькими кросс-функциональными командами, техническими лидерами, портфелем проектов и внутренними бизнес-системами.

Ключевые задачи и результаты:
- Стабилизировал работу департамента после ухода ключевого лидера, разделил большую команду на управляемые продуктовые направления, выстроил приоритизацию и процессы delivery.
- Внедрил инфраструктурные и engineering-практики: self-hosted/AWS, IaC, CI/CD, Git flow, DBVC.
- Снизилось число аварий на web-сервисах примерно в 3 раза за полгода, повысилась стабильность.
- Развитие мониторинга продуктов, внедрение метрик доступности позволило управлять инцидентами.
- Организовал перевод BI/QlikView на данные КХД, запустил слой проверок DQ, организовал миграцию управленческой отчетности на EDW.

#### Июнь 2020 — Ноябрь 2020

Руководитель проектов

Управлял проектами разработки внутренних web-сервисов для бизнес-функций: сбор требований, приоритизация с бизнесом, управление разработкой, ожиданиями, сроками, приемкой и внедрением.

### ООО «Информсвязь Сервис»

Информационные технологии, системная интеграция, разработка программного обеспечения.

#### Март 2018 — Май 2020

Менеджер проекта

Проектное управление в IIoT: средний уровень — железо, верхний уровень — frontend, backend. Разработка серверного программного обеспечения, web, электроники, системная интеграция, проектирование. Сводил воедино требования заказчика, технические и ресурсные ограничения, интересы бизнеса и команду для получения результата.

## Образование

Высшее
Уральский федеральный университет имени первого Президента России Б.Н. Ельцина, Екатеринбург
2011
Высшая школа экономики и менеджмента, Финансы и кредит

## Повышение квалификации, курсы

Взлет Т1: из эксперта IT в лидеры команд
2024
Т1 Цифровая академия, Teamlead

Luxoft training
2021
Администрирование Jira

НПО Сапфир
2021
PostgreSQL dev-1

GeekBrains от Mail.ru Group
2020
HTML/CSS. Интерактивный курс

НОУ ДПО «Урало-Сибирский центр развития персонала «Фабрика управляющих проектами»
2019
Интенсивная подготовка к сертификации по международному стандарту управления проектами IPMA. Повышение квалификации

## Навыки

Русский — родной
Английский — B2, средне-продвинутый

AI Infrastructure; AI Platform; AgentOps; Agentic Systems; External Memory; Semantic Retrieval; MCP; Self-hosted Infrastructure; Docker; Linux; Git; Markdown-first Knowledge Base; Basic Memory/MCP; OpenClaw; SQLite FTS5; LLM Chat Ingestion; Platform Engineering; Infrastructure Transformation; DevOps; CI/CD; Kubernetes; VM Infrastructure; OpenStack; Capacity Planning; Technical Program Management; Risk Management; Cross-functional Coordination; Stakeholder Management; Analytical skills; Information Technology.

## Дополнительная информация

Английский B2.
Сертификат IPMA №4460.
