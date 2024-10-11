<h1 align="center">Daily Planner </h1>
<h3 align="center">Приложение для планирования задач</h3>
В нем есть функции создания дел с указанием и созданием их категорий (например, покупки), даты и времени их выполнения, удобный интерфейс с распределением дел по периодам от дня до года, а также вывод статистики по выполнению поставленных задач.
<h3 align="center">Устройства бэка</h3>
Бэк написан на C# ASP.NET Core. Для БД выбран PostgreSQL.
# Expenser

Expenser is a personal finance tracking application designed to simplify financial management and help users achieve their budget goals.

## What is Expenser for?

This application is intended for simplifying personal finance management and tracking goals set for budgets.

## Features

### Income and Expense Tracking:
- Add and classify all financial transactions.
- Support for multi-currency operations.
- Ability to add tags to transactions.

### Budgeting:
- Visualization of balance changes over time.
- View transactions by various criteria.

### Goals and Savings:
- Set financial goals for income and expenses.
- Track progress towards financial goals.

### Intuitive User Interface:
- User-friendly navigation and a clear structure.
- Support for both dark and light themes for better user comfort.

### Cross-platform Support:
- Available on mobile devices and through the web interface.
- Data synchronization across all devices.

## Frontend Structure

The application uses the **Ionic Capacitor** platform, allowing us to build PWA and native mobile applications for iOS and Android using **HTML, CSS, and JS**. The frontend framework chosen is **Vue.js** together with the **PrimeVue** component library.

### User Interface Prototype

The interface was designed using **Figma**.

#### Login and Registration Screens:
![Login](link_to_image1) ![Registration](link_to_image2)

#### Home Page and Adding Transactions:
![Home](link_to_image3) ![Add Transaction](link_to_image4) ![Transaction List](link_to_image5)

#### Budget and Goals:
![Budget](link_to_image6) ![Goals](link_to_image7)

#### Profile and Settings:
![Profile](link_to_image8) ![Settings](link_to_image9)

## Backend Structure

The backend is written in **C#** using **ASP.NET Core**, and the database is **PostgreSQL**.

## How to Run the Project

### Frontend Setup
1. Clone the repository.
2. Navigate to the `frontend` folder.
3. Install dependencies:
   ```bash
   npm install
