# BudgetTracker

Android-приложение для учета личных финансов и управления бюджетом.

Проект реализован на Kotlin и демонстрирует работу с локальным хранением данных, навигацией между экранами и dependency injection.

## Screenshots

<p align="center">
  <img src="screenshots/home.png" width="220">
  <img src="screenshots/balance.png" width="220">
  <img src="screenshots/income.png" width="220">
  <img src="screenshots/add_expense.png" width="220">
</p>

## Features

- просмотр общей суммы
- отдельный учет доходов и расходов
- управление счетами
- поиск по операциям
- добавление доходов
- добавление расходов
- выбор категории расхода
- выбор счета
- указание суммы, даты и комментария
- редактирование и удаление записей
- локальное хранение данных

## Tech Stack

- Kotlin
- Android SDK
- XML
- Room
- Hilt
- Navigation Component
- Safe Args
- ViewBinding
- RecyclerView
- Material Components

## Architecture

Приложение построено на нескольких Fragment-экранах и использует Navigation Component для переходов между ними.

Данные сохраняются локально с использованием Room.

Hilt используется для dependency injection.

## Main Screens

- Home — общая сумма, доходы и расходы
- Balance — список счетов
- Income — список доходов и поиск
- Expenses — список расходов и поиск
- Add Account — создание и редактирование счета
- Add Income — создание и редактирование дохода
- Add Expense — создание и редактирование расхода

## Project Structure

```text
app/
├── data/
├── di/
├── ui/
│   ├── balance/
│   ├── income/
│   ├── expences/
│   └── adddata/
├── MainActivity
└── App
<img width="1952" height="1078" alt="image" src="https://github.com/user-attachments/assets/d1eed64e-eda4-435e-83f7-3964df62b37f" />
