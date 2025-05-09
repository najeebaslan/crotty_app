# Recharge Cards App <img src="assets/logo.png" width="40" height="40">

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Flutter](https://img.shields.io/badge/flutter-3.19.5-blue)
![Dart](https://img.shields.io/badge/dart-3.3.0-blue)

<!-- PROJECT LOGO -->
<div align="center">
  <img src="assets/logo.png" alt="Logo" width="200">
  
  <h1>Recharge Cards Management App</h1>
  
  <p>
    A comprehensive solution for managing recharge cards for service providers and customers
  </p>

## About The Project

The recharge cards app provides an innovative solution for purchasing recharge cards digitally without the need for physical cards, with additional features such as:
✔ Track past purchases 
✔ Exclusive offers 
✔ Receive cards instantly on your mobile 
✔ Avoid the hassle of losing cards

  <div>
    <a href="#">
      <img src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white" height="60">
    </a>
    <a href="#">
      <img src="https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=app-store&logoColor=white" height="60">
    </a>
  </div>
</div>

## 📱 App Screenshots

<div align="center">
  <table>
    <tr>
      <td><img src="screenshots/login.jpg" width="200"></td>
      <td><img src="screenshots/home.jpg" width="200"></td>
      <td><img src="screenshots/cards.jpg" width="200"></td>
      <td><img src="screenshots/map.jpg" width="200"></td>
    </tr>
    <tr>
      <td><img src="screenshots/reports.jpg" width="200"></td>
      <td><img src="screenshots/notifications.jpg" width="200"></td>
      <td><img src="screenshots/profile.jpg" width="200"></td>
      <td><img src="screenshots/dark_mode.jpg" width="200"></td>
    </tr>
  </table>
</div>

## ✨ Key Features

- 🔍 Discover nearby available networks
- 💳 Purchase network cards from any provider
- 🛡️ Secure card storage with encryption
- 📊 Comprehensive purchase history tracking
- 🔔 Real-time notifications for promotions
- 🗺️ Network location visualization
- 📦 Easy-to-use purchase process
- 🌙 Dark mode support

## 🛠 Core Technical Features

- **Backend**: Node.js with Express
- **Database**: MongoDB with Redis caching
- **Authentication**: Email/Password & Google Sign-In
- **Notifications**: Firebase Messaging + Flutter Local Notifications
- **State Management**: BLoC Pattern
- **UI**: Fully responsive with advanced animations
- **Maps**: Google Maps integration
- **API**: RESTful with Dio client

## 🛠️ Development Skills Applied

### Backend Development
- Node.js with Express framework
- MongoDB database design
- Redis for caching and performance
- RESTful API development
- JWT authentication

### Mobile Development
- Flutter with Clean Architecture
- BLoC state management
- Firebase Messaging integration
- Flutter Local Notifications
- Google Maps integration
- Advanced animation implementation
- Dio for network operations
- Responsive UI design

### Tools & Methodologies
- Postman for API testing
- Project requirement planning
- Clean Architecture implementation
- Git version control
- Agile development

## 🧩 Application Structure (Clean Architecture)
```
lib/
├── core/
│ ├── constants/
│ ├── errors/
│ ├── network/
│ ├── usecases/
│ └── utils/
├── features/
│ ├── auth/
│ │ ├── data/
│ │ ├── domain/
│ │ └── presentation/
│ ├── networks/
│ │ ├── data/
│ │ ├── domain/
│ │ └── presentation/
│ ├── settings/
│ │ ├── data/
│ │ ├── domain/
│ │ └── presentation/
│ ├── reports/
│ │ ├── data/
│ │ ├── domain/
│ │ └── presentation/
│ ├── card/
│ │ ├── data/
│ │ ├── domain/
│ │ └── presentation/
│ └── purchases/
│ ├── data/
│ ├── domain/
│ └── presentation/
├── injection_container.dart
└── main.dart
```


## 🏛 Technical Architecture

```mermaid
graph TD
    A[Presentation Layer] --> B[Business Logic Layer]
    B --> C[Data Layer]
    C --> D[External APIs]
    C --> E[Local Storage]
    B --> F[Google Maps API]
    B --> G[Firebase Messaging]
    C --> H[Card Inventory]
    C --> I[Sales Reports]

```
## 📊 Project Workflow

```mermaid
 sequenceDiagram
    participant A as Application
    participant B as Business Logic
    participant C as Data Layer
    participant D as External APIs
    participant E as Local Storage
    participant F as Google Maps API
    participant G as Firebase Messaging
    participant H as Card Inventory
    participant I as Sales Reports
    A->>B: Request data from Business Logic
    B->>C: Fetch data from Data Layer
    C->>D: Call external APIs
    C->>E: Store data in local storage
    C->>F: Use Google Maps API
    C->>G: Use Firebase Messaging
    C->>H: Manage card inventory
    C->>I: Generate sales reports
    B-->>A: Receive data from Business Logic   
```
