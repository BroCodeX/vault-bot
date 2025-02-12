# Telegram Bot for HashiCorp Vault with Kafka

[![Maintainability](https://api.codeclimate.com/v1/badges/98731fcbac73124c516b/maintainability)](https://codeclimate.com/github/BroCodeX/BroX-VaultBot/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/98731fcbac73124c516b/test_coverage)](https://codeclimate.com/github/BroCodeX/BroX-VaultBot/test_coverage)

Telegram-бот на Java Spring для управления чувствительными данными в HashiCorp Vault с использованием Spring Kafka для асинхронной обработки запросов.

---

<summary><strong>📋 Оглавление</strong></summary>

1. [Описание](#описание)
2. [Функции](#функции)
3. [Технологии](#технологии)
4. [Установка](#установка)
5. [Использование](#использование)
6. [Архитектура](#архитектура)
7. [Лицензия](#лицензия)

---

## Описание

Бот позволяет сохранять, обновлять, удалять и получать чувствительные данные (например, пароли) в HashiCorp Vault. Kafka используется для асинхронной обработки запросов.

---

## Функции

<details>
<summary><strong>✨ Основные</strong></summary>

- Сохранение данных в Vault.
- Обновление и удаление данных.
- Получение данных по запросу.
- Аутентификация через Telegram ID.
</details>

<details>
<summary><strong>🔧 Дополнительные</strong></summary>

- Логирование операций.
- Уведомления об успехе/ошибках.
- Поддержка нескольких пользователей.
</details>

---

## Технологии

<details>
<summary><strong>🛠️ Стек</strong></summary>

- Java 17+
- Spring Boot 3.x
- TelegramBots
- Spring Vault
- Kafka (Spring-kafka)
- H2/PostgreSQL
- SLF4J
- Gradle 8.7
- Docker Compose
</details>

---

## Установка

<details>
<summary><strong>🚀 Инструкция</strong></summary>

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/ваш-username/ваш-репозиторий.git
   cd ваш-репозиторий
