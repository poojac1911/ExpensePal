---

# 💰 ExpensePal

**ExpensePal** is a personal expense tracking Android application built with **Kotlin** and **Firebase**. It enables users to effortlessly log and categorize their expenses, get summaries, and store data securely. The app offers a modern, intuitive UI and supports local and cloud storage for scalability and flexibility.

---

## ✨ Features

- ➕ **Add Expenses** – Log daily expenses with details like amount, category, date, and description.
- 📋 **View History** – Browse a list of past expenses.
- 🗂️ **Categorization** – Group expenses by category.
- 📊 **Expense Summary** – View summaries by day, week, or month.
- 🔒 **Firebase Authentication** – Sign in securely with Google.
- ☁️ **Firebase Firestore** – Sync expense data across devices.
- 🎨 **Material UI** – Clean and intuitive user interface.

---

## 🛠️ Tech Stack

- 🧠 **Kotlin** – Modern, concise Android programming.
- 🏗 **MVVM Architecture** – For clean, maintainable code.
- 🗃️ **Room Database** – Local persistence.
- 🔥 **Firebase Suite**:
    - **Authentication** – Secure login via Google.
    - **Cloud Firestore** – Real-time data sync and cloud storage.
- ⚙️ **Gradle** – Build automation.
---

## 🚀 Getting Started

### 📋 Prerequisites

- Android Studio
- Firebase Project with:
    - Authentication enabled (Google)
    - Firestore Database setup
- Android device or emulator

### 🔧 Installation

```bash
git clone https://github.com/poojac1911/ExpensePal.git
```

1. Open in **Android Studio**.
2. Sync Gradle and let it install dependencies.
3. Add your `google-services.json` file to the `app/` directory from your Firebase project.
4. Run the app on a device/emulator with `Shift + F10`.

---

## 📁 Project Structure

```
ExpensePal/
├── app/
│   ├── data/             # Room DB, Firestore services
│   ├── ui/               # Activities, ViewModels, Adapters
│   ├── auth/             # Firebase Auth handlers
│   └── utils/            # Helper classes
├── google-services.json  # Firebase config file (not in repo)
├── build.gradle
└── settings.gradle
```

---

## 📌 TODO

- 📈 Visualize expenses with pie/bar charts
- 🔔 Add notifications for budget limits
- 🧾 Export data to CSV or PDF
- 🌐 Dark mode support

---

## 🤝 Contributing

Contributions are welcome! Fork the repository and submit a pull request.

---

## 📬 Contact

📧 For any questions, please open an issue or reach out via GitHub.

---