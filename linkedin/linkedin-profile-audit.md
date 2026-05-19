# LinkedIn Profile Audit

Профиль: https://www.linkedin.com/in/iv-medvedev/

Дата аудита: 2026-05-19

## Статус доступа

Прямой публичный доступ к профилю через браузерный инструмент и `curl` получить не удалось: LinkedIn отдает authwall / redirect на авторизационную страницу.

Поисковая выдача по `iv-medvedev` и точному URL не дала надежного публичного сниппета с содержанием профиля. Поэтому аудит ниже не является построчной сверкой текущего LinkedIn-профиля. Это первый безопасный слой актуализации: что нужно проверить и обновить вручную в LinkedIn на основе текущего публичного карьерного портфолио.

## Источники для актуализации

- `ai-readable-professional-profile.md` — основной набор фактов и кейсов.
- `target-roles.md` — карта целевых ролей и позиционирования.
- `resumes/technical-program-manager-hh.md` — структура и формулировки для Technical Program Manager.
- `resumes/internal-developer-platform-lead-hh.md` — структура и формулировки для Internal Developer Platform Lead.
- `resumes/ai-infrastructure-program-manager-hh.md` — рамка для AI Infrastructure / AgentOps направления.
- `AGENTS.md` и `README.md` — правила публичной безопасности и сохранения авторского голоса.

## Целевое позиционирование LinkedIn

Основной профиль должен читаться как:

Technical Program Manager / Infrastructure & Platform Transformation с опытом управления mission-critical инфраструктурными и delivery-программами, CI/CD migration, Kubernetes/VM-инфраструктурой, OpenStack/AstraLinux migration, platform engineering, production readiness, capacity planning и кросс-командной координацией.

Второй слой позиционирования:

Internal Developer Platform / Platform Engineering lead: DevOps-команда как внутренний сервис, 4 магистральных пайплайна, engineering standards, onboarding, quality gates, developer productivity, снижение трудоемкости релизов и ускорение delivery.

Дифференцирующий слой:

AI infrastructure / AgentOps через личный self-hosted pet-lab. Формулировать строго как personal engineering project / self-hosted lab / actively evolving prototype, а не как production enterprise AI platform.

## Что проверить в текущем LinkedIn

1. Headline
   - Убрать фокус на generic project management, если он есть.
   - Поднять выше Technical Program Management, Infrastructure / Platform Transformation, CI/CD, Kubernetes, DevOps / Platform Engineering.
   - Не позиционироваться как pure Engineering Manager, Product Manager, Cloud Architect или AI Engineer.

2. About
   - Обновить summary под текущую роль: infrastructure/platform/delivery programs.
   - Добавить масштаб: 3000+ VM, 15+ Kubernetes clusters, 100+ microservices, 30-40 releases per quarter, 100 000 RPS, mission critical level.
   - Коротко показать AI pet-lab как дополнительный hands-on learning / self-hosted lab.
   - Не превращать AI pet-lab в production AI / enterprise RAG / commercial AI product.

3. Experience
   - Исправить периодизацию Иннотех:
     - Август 2025 — настоящее время: Platform Infrastructure & DevOps Lead / Руководитель инфраструктуры и DevOps стрима.
     - Апрель 2022 — Август 2025: Team Lead / Integration Services Lead → DevOps Team Lead.
   - Не дробить период Апрель 2022 — Август 2025 на роли с выдуманными датами.
   - Исправить периодизацию Галамарт:
     - Июнь 2020 — Ноябрь 2020: Руководитель проектов.
     - Ноябрь 2020 — Апрель 2022: Руководитель департамента управления данными и web-сервисов / Head of Internal Systems Development.
   - Информсвязь Сервис оставить отдельной ролью: Март 2018 — Май 2020, Менеджер проекта.

4. Featured / Publications / Projects
   - Добавить ссылку на публичный репозиторий professional-profile, если профиль LinkedIn должен вести к AI-readable портфолио.
   - В описании ссылки не раскрывать private source materials, внутренние детали работодателей или сырые источники.
   - Возможная подпись: Public AI-readable professional profile and role-specific resume workspace.

5. Skills
   - Поднять выше: Technical Program Management, Infrastructure Transformation, Platform Engineering, DevOps, CI/CD, Kubernetes, OpenStack, Private Cloud, Production Readiness, Capacity Planning, Risk Management, Cross-functional Coordination.
   - Для AI-направления добавить аккуратно: AI Infrastructure, AgentOps, Agentic Systems, External Memory, Semantic Retrieval, MCP, Self-hosted Infrastructure.
   - Не добавлять ML Engineering, Model Training, Production MLOps, AI Engineer как центральные навыки.

6. Education / Courses
   - Сохранить курсы из резюме.
   - Не удалять доменные бренды, относящиеся к обучению, например `GeekBrains от Mail.ru Group`.
   - IPMA оставить в Additional information / Certifications, если в LinkedIn есть подходящее поле.

## Риски текущего профиля

- Если профиль сейчас построен вокруг старых ролей руководителя проектов / руководителя департамента внутренних систем, он будет слабее матчиться на Infrastructure TPM и Platform Engineering.
- Если AI pet-lab описан слишком сильно, профиль может выглядеть как заявка на production AI platform experience, которого источник не подтверждает.
- Если профиль слишком сухой и корпоративный, он потеряет авторский голос. Текущие правила проекта разрешают сохранять живые, сырые и эмоционально окрашенные формулировки, если они намеренно присутствуют в одобренном источнике и не создают публичных рисков.
- Если оставить слишком много деталей работодателей и внутренних ограничений, профиль станет менее безопасным для публичной площадки.

## Первые шаги актуализации

1. Обновить headline по одному из вариантов из `linkedin-update-draft.md`.
2. Заменить / переписать About на новый блок из `linkedin-update-draft.md`.
3. В текущей роли Иннотех поднять наверх infrastructure lifecycle, CI/CD, capacity planning, production readiness и cross-functional coordination.
4. В предыдущей роли Иннотех явно указать два этапа внутри одного периода: сначала Integration Services Lead, затем DevOps Team Lead.
5. Добавить короткий Projects-блок про self-hosted AI-agent lab с честными ограничениями.
6. Пересобрать Skills под целевые роли из `target-roles.md`.
7. Проверить, что профиль не содержит телефона, email, Telegram, IP, токенов, конфигов и внутренних названий закрытых систем.
