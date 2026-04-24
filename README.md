# 🥗 Calorie Tracking App

A simple yet powerful Calorie Tracking Application built to help users monitor their daily food intake, manage nutrition, and stay aligned with their health goals.

This project demonstrates clean code principles, object-oriented programming, and practical real-world application design.

---

## 🚀 Features

### 👤 User Management
- Create and manage user profiles
- Set personal goals (weight loss, maintenance, gain)
- Configure daily calorie targets

### 🍎 Food Tracking
- Add food items with:
  - Name
  - Calories
  - Quantity
  - Category (e.g., Breakfast, Lunch, Dinner, Snacks)
- View all consumed food items per day
- Edit or remove food entries

### 📊 Daily Calorie Overview
- Track total calories consumed
- Compare intake vs daily goal
- Show remaining calories

### 📅 History Tracking
- View calorie intake per day
- Maintain a log of previous days
- Analyze eating patterns

### 🧠 Smart Insights (Optional / Advanced)
- Warn when exceeding calorie limit
- Suggest healthier alternatives
- Provide simple nutrition tips

### 💾 Data Persistence
- Save data to file (CSV / JSON)
- Load existing data on application startup

---

## 🏗️ Project Structure

```bash
calorie-tracker/
│
├── src/
│   ├── model/            # Domain models (User, FoodItem, Meal, etc.)
│   ├── service/          # Business logic (CalorieService, TrackingService)
│   ├── repository/       # Data handling (File storage)
│   ├── ui/               # CLI or UI layer
│   └── Main.java         # Entry point
│
├── data/
│   └── meals.csv         # Stored user data
│
├── README.md
└── pom.xml (if using Maven)
