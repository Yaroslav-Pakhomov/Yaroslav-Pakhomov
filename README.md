# Привет, я Ярослав Пахомов 👋

**PHP Backend Developer / Laravel Developer**

Более 5 лет занимаюсь коммерческой PHP-разработкой.

Основная специализация — backend-разработка на Laravel: REST API, PostgreSQL, Redis, очереди, проектирование бизнес-логики и оптимизация производительности.

В коммерческих проектах занимаюсь разработкой и развитием backend-систем, проектированием БД и API, оптимизацией SQL, кешированием, асинхронной обработкой задач, production support и code review.

---

## Основной стек

**Backend**

`PHP` · `Laravel` · `Yii2` · `REST API`

**Databases & Cache**

`PostgreSQL` · `MySQL` · `MariaDB` · `Redis`

**Architecture & Engineering**

`OOP` · `SOLID` · `Service Layer` · `DDD principles` · `Database Transactions` · `Queue / Background Jobs`

**Testing & Quality**

`PHPUnit` · `Feature Tests` · `PHPStan / Larastan` · `Laravel Pint` · `Rector`

**Infrastructure**

`Docker` · `Laravel Sail` · `Linux` · `Nginx` · `GitHub Actions`

**Frontend**

`Vue 3` · `Inertia.js` · `JavaScript` · `TailwindCSS`

---

# Featured Project

## [LedgerPay](https://github.com/Yaroslav-Pakhomov/ledgerpay-platform)

**Fintech backend / portfolio project**

`Laravel 13` · `PHP 8.5` · `PostgreSQL` · `Redis Queue` · `Sanctum` · `Docker` · `Vue 3` · `Inertia`

Backend-система для работы со счетами и денежными операциями.

### Что реализовано

* REST API;
* аутентификация через Laravel Sanctum;
* deposit / withdrawal / transfer;
* идемпотентность денежных операций через `Idempotency-Key`;
* транзакции БД;
* `SELECT ... FOR UPDATE` / `lockForUpdate()` для конкурентного доступа;
* стабильный порядок блокировки счетов для снижения риска deadlock;
* асинхронная обработка транзакций через Redis Queue;
* immutable ledger;
* audit log;
* Problem Details JSON;
* `X-Request-Id` и correlation logging;
* OpenAPI / Swagger;
* Feature Tests;
* PHPStan / Larastan;
* Rector;
* Laravel Pint;
* CI через GitHub Actions;
* backoffice на Vue 3 + Inertia.

Проект демонстрирует подход к проектированию backend-систем, где важны консистентность данных, повторяемость запросов, конкурентный доступ и наблюдаемость.

🔗 **Repository:** [github.com/Yaroslav-Pakhomov/ledgerpay-platform](https://github.com/Yaroslav-Pakhomov/ledgerpay-platform)

---

# Другие проекты

## [Laravel / Vue E-commerce](https://github.com/Yaroslav-Pakhomov/docker-mysql-laravel-vue-spa-store)

Интернет-магазин на Laravel + Vue + Inertia.

Реализованы:

* каталог товаров;
* административная панель;
* CRUD;
* связи Eloquent;
* поиск;
* пагинация;
* работа с изображениями;
* корзина;
* оформление заказов.

**Stack:** `Laravel` · `Vue` · `Inertia` · `MySQL` · `Docker`

🔗 **Repository:** [github.com/Yaroslav-Pakhomov/docker-mysql-laravel-vue-spa-store](https://github.com/Yaroslav-Pakhomov/docker-mysql-laravel-vue-spa-store)

---

## [Laravel / Vue Chirps](https://github.com/Yaroslav-Pakhomov/docker-mysql-laravel-vue-spa-chirps)

SPA-приложение с авторизацией и CRUD объявлений.

Реализованы:

* авторизация;
* CRUD объявлений;
* Laravel Breeze;
* SPA-интерфейс;
* интеграция Laravel + Vue через Inertia;
* Docker-окружение.

**Stack:** `Laravel` · `Vue` · `Inertia` · `Laravel Breeze` · `TailwindCSS` · `Docker`

🔗 **Repository:** [github.com/Yaroslav-Pakhomov/docker-mysql-laravel-vue-spa-chirps](https://github.com/Yaroslav-Pakhomov/docker-mysql-laravel-vue-spa-chirps)

---

# Дополнительный опыт

Работал с:

`Drupal 9` · `RabbitMQ` · `ClickHouse` · `PhpSpreadsheet` · `Go`

---

# Сейчас интересуюсь

* проектированием backend-архитектуры;
* производительностью PostgreSQL;
* конкурентным доступом к данным;
* очередями и асинхронной обработкой;
* архитектурой API;
* качеством и тестируемостью PHP-кода.
