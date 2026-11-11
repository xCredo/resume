# Привет, я Владислав Журбенко

**Frontend-разработчик · TypeScript · React · Новосибирск**

[![Telegram](https://img.shields.io/badge/Telegram-@xCredo__o-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://t.me/xCredo_o)
[![Email](https://img.shields.io/badge/Email-vladern12@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:vladern12@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-xCredo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/xCredo)

## Обо мне

- Пишу на TypeScript + React, проектирую модульную архитектуру: DI, паттерны Adapter / PageObject / Observer.
- В рамках ВКР по заказу Т-Банк адаптировал open-source расширение [jira-helper](https://github.com/jira-helper/jira-helper) для Jira Cloud — мой PR после ревью мейнтейнера слит в основную ветку проекта с 12 000+ пользователей.
- Прошёл полный open-source цикл: анализ чужого кода → реализация → ревью → merge.
- Тесты — не опция: Vitest, Cypress, BDD (Gherkin).
- Свободно читаю техническую документацию на английском.

## Избранный проект: jira-helper

[jira-helper](https://github.com/jira-helper/jira-helper) — расширение для Chromium-браузеров и Firefox, расширяющее возможности Jira: WIP-лимиты по колонкам, людям и свимлейнам, обогащение карточек задач (связи, прогресс-бары, бейджи по JQL), улучшенный счётчик дней. 12 000+ активных пользователей: разработчики, аналитики, QA, тимлиды, PM.

[![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-установить-4285F4?style=flat-square&logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/jira-helper/egmbomekcmpieccamghfgjgnlllgbgdl)

**Мой вклад — адаптация для Jira Cloud.** Cloud устроен принципиально иначе, чем Server: другая DOM-структура, API и идентификация пользователей.

- Спроектировал и реализовал Cloud-версию с нуля: разделил доменную логику и слой адаптеров — теперь один функционал подключается и к Server, и к Cloud.
- Модульная архитектура на DI-контейнере (dioma), инфраструктурные адаптеры (Adapter, PageObject) — 100% доменной логики переиспользуется между версиями.
- Реализовал реактивное обновление UI при изменении DOM доски (MutationObserver + система подписок).
- Настроил хранение настроек через Jira REST API (Board Properties) с fallback-механизмом на localStorage.
- Зарефакторил унаследованный код, устранив ~400 строк дублирующей бизнес-логики.
- Покрыл код 1743 юнит-тестами (Vitest) и компонентными тестами (Cypress + Gherkin/BDD).

Репозиторий · [PR #36](https://github.com/jira-helper/jira-helper/pull/36) · [мои коммиты](https://github.com/jira-helper/jira-helper/commits?author=xCredo) · [Chrome Web Store](https://chromewebstore.google.com/detail/jira-helper/egmbomekcmpieccamghfgjgnlllgbgdl)

## Стек

[![My Skills](https://skillicons.dev/icons?i=ts,js,react,vite,html,css,git,github,gitlab,nodejs)](https://skillicons.dev)

| Категория | Технологии |
|---|---|
| Языки | TypeScript, JavaScript |
| Фронтенд | React 18, Vite, Ant Design, HTML/CSS |
| Архитектура | DI (dioma), Adapter, Observer, PageObject |
| Тестирование | Vitest, Cypress, BDD (Gherkin) |
| Инструменты | Git, GitHub, GitLab, ESLint, Husky, CI/CD |

## Пет-проекты

- **Telegram-бот для Google Таблиц** — Google Apps Script + Telegram Bot API: парсинг изменений в Forms/Sheets, логика распределения бюджета, уведомления.
- **Учебные веб-проекты (СибГУТИ)** — тематический сайт, браузерная игра: вёрстка, логика на JS, работа с DOM.

## Образование и сертификаты

- **СибГУТИ**, бакалавр (2022–2026) — 02.03.02 «Фундаментальная информатика и информационные технологии», профиль «Системное программное обеспечение». Фундаментальная база: алгоритмы, ОС, системное программирование на C/C++.
- **Samsung Innovation Campus IT Academy** — трек «Интернет вещей» (IoT), 240 академических часов, выпускной проект защищён с отличием.

## Контакты

- Telegram: [@xCredo_o](https://t.me/xCredo_o)
- Email: vladern12@gmail.com
- Открыт к удалёнке, гибриду и релокации.
