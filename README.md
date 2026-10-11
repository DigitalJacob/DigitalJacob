# Hi, I'm Jacob 👋

**Python backend developer building production-grade Telegram bots** - booking systems,
automation and business workflows on aiogram 3, asyncio, PostgreSQL and Docker.

I care about the parts that keep a bot alive after launch: clean architecture,
transactional data integrity, tests and CI.

📍 Saint Petersburg · 💬 [Telegram](https://t.me/kreisleiter) · Open to freelance & full-time

---

## ⭐ Featured project - [booking_bot](https://github.com/DigitalJacob/booking_bot)

Appointment booking bot for small service businesses (barbers, nail studios, tutors).

- **Layered architecture** - domain logic has no aiogram / SQL imports; persistence via
  `typing.Protocol` ports, so the domain is tested in-memory in under a second
- **Data integrity** - one DB transaction per update; Postgres exclusion constraint
  makes double booking impossible even under races
- **Real-world flows** - weekly or monthly schedules, time off and breaks with conflict
  warnings, confirm / decline / cancel with reasons, evening and hour-ahead reminders
- **Product details** - sticky inline hub navigation, ru / en i18n, personal-data consent
- **Engineering** - raw SQL repositories, versioned migrations, Docker Compose,
  GitHub Actions CI (ruff, mypy, pytest + Postgres integration tests)

`Python 3.13` `aiogram 3` `PostgreSQL 17` `Redis` `psycopg 3` `Docker` `pytest`

---

## 🛠 Stack

**Core:** Python · asyncio · aiogram 3  
**Data:** PostgreSQL · Redis · raw SQL · migrations  
**Infra & quality:** Docker Compose · GitHub Actions · pytest · ruff · mypy

## 🧩 Other projects

- [book_bot](https://github.com/DigitalJacob/book_bot) - reading bot with bookmarks
- [echo_bot_PostgreSQL](https://github.com/DigitalJacob/echo_bot_PostgreSQL) - aiogram + PostgreSQL basics
- [rock_paper_scissors_bot](https://github.com/DigitalJacob/rock_paper_scissors_bot) - game bot

---

**Need a Telegram bot for your business?** Message me on [Telegram](https://t.me/kreisleiter) -
I'll help scope it, build it and ship it with Docker.

---

# Привет, меня зовут Яков 👋

**Python backend-разработчик, делаю Telegram-боты продакшен уровня** - записи,
автоматизация и бизнес-процессы на aiogram 3, asyncio, PostgreSQL и Docker.

Мои приоритеты: чистая архитектура, целостность данных в транзакциях, тесты и CI.

📍 Санкт-Петербург · 💬 [Telegram](https://t.me/kreisleiter) · Открыт к фрилансу и полной занятости

---

## ⭐ Главный проект - [booking_bot](https://github.com/DigitalJacob/booking_bot)

Бот записи для малого бизнеса (барбершоп, мастер маникюра, репетитор, тренер).

- **Слоистая архитектура** — domain без импортов aiogram / SQL; порты через
  `typing.Protocol`, unit-тесты domain на in-memory фейках за доли секунды
- **Целостность данных** — одна DB-транзакция на апдейт; exclusion constraint в Postgres
  не даёт двойной записи даже при гонках
- **Реальные сценарии** — недельное или месячное расписание, выходные и перерывы
  с предупреждением о конфликтах, confirm / decline / cancel с причиной,
  напоминания вечером накануне и за час
- **Продукт** — sticky inline-хаб, ru / en, согласие на обработку персональных данных
- **Инженерия** — raw SQL-репозитории, версионированные миграции, Docker Compose,
  GitHub Actions (ruff, mypy, pytest + интеграция с Postgres)

`Python 3.13` `aiogram 3` `PostgreSQL 17` `Redis` `psycopg 3` `Docker` `pytest`

---

## 🛠 Стек

**Core:** Python · asyncio · aiogram 3  
**Data:** PostgreSQL · Redis · raw SQL · миграции  
**Infra & quality:** Docker Compose · GitHub Actions · pytest · ruff · mypy

## 🧩 Другие проекты

- [book_bot](https://github.com/DigitalJacob/book_bot) - бот для чтения с закладками
- [echo_bot_PostgreSQL](https://github.com/DigitalJacob/echo_bot_PostgreSQL) - база aiogram + PostgreSQL
- [rock_paper_scissors_bot](https://github.com/DigitalJacob/rock_paper_scissors_bot) - игровой бот

---

**Нужен Telegram-бот для бизнеса?** Напиши в [Telegram](https://t.me/kreisleiter) -
помогу сформулировать задачу, собрать и задеплоить на Docker.
