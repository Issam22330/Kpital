# Kpital 📊

Kpital is a comprehensive personal finance and wealth management application for Android. Unlike traditional expense trackers, Kpital bridges the gap between daily spending and long-term investment growth, providing users with a holistic view of their financial health.

## 🌟 Overview

Managing money is more than just recording expenses; it's about understanding habits and building wealth. Kpital helps users track every cent, manage complex investment portfolios, and receive intelligent insights to make better financial decisions.

## ✨ Key Features

- **Holistic Dashboard**: A real-time overview of total capital, including savings, cash, and investments.
- **Transaction Tracking**: Detailed logging of income and expenses with category management and smart search.
- **Investment Portfolio**: Track various asset types (Stocks, Crypto, ETFs, Real Estate) with ROI calculations and historical snapshots.
- **Smart Financial Insights**: Automated analysis of spending patterns, budget warnings, and monthly summaries that help identify anomalies and saving opportunities.
- **Savings Goals**: Set, track, and visualize progress toward specific financial milestones.
- **Real-time Sync**: Full cloud integration ensures data is always safe and accessible across devices.

## 🛠 Tech Stack

- **Language**: Java (Android SDK)
- **Architecture**: MVVM (Model-View-ViewModel) for clean separation of concerns.
- **Backend**: 
  - **Firebase Firestore**: Scalable NoSQL database for real-time data synchronization.
  - **Firebase Auth**: Secure user authentication and session management.
- **Dependency Injection**: Hilt (Dagger) for robust and testable code.
- **Jetpack Components**: 
  - Navigation Component
  - ViewBinding
  - ViewModel & LiveData
- **Data Visualization**: MPAndroidChart for interactive financial trends.

## 🏗 Architecture

The project follows modern Android development patterns to ensure scalability and maintainability:

- **Domain Layer**: Contains business logic, models, and repository interfaces.
- **Data Layer**: Handles data source implementations (Firestore, Local Preferences).
- **UI Layer**: Fragment-based UI using ViewBinding and LiveData to reactively update the interface.

## 💎 Why Kpital?

Most apps focus either on budgeting or on investing. Kpital is valuable because it integrates both. It treats a user's finances as a single ecosystem, allowing them to see how their morning coffee habit directly impacts their long-term investment goals. The inclusion of "Smart Insights" moves the app from a passive ledger to an active financial consultant.

---

## 🚀 Getting Started

1. Clone the repository.
2. Register your app in the [Firebase Console](https://console.firebase.google.com/).
3. Download the `google-services.json` and place it in the `/app` directory.
4. Build and run using Android Studio.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
