# Recharge Cards App <img src="https://firebasestorage.googleapis.com/v0/b/meamarmanager.appspot.com/o/network_client_app_logo%2Flogo_with_name.png?alt=media&token=2ebe157a-587d-4d52-9b17-701d0dee79be" width="40" height="40">

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Flutter](https://img.shields.io/badge/flutter-3.19.5-blue)
![Dart](https://img.shields.io/badge/dart-3.3.0-blue)

<!-- PROJECT LOGO -->
<div align="center">
  <img src="https://firebasestorage.googleapis.com/v0/b/meamarmanager.appspot.com/o/network_client_app_logo%2Flogo_with_name.png?alt=media&token=2ebe157a-587d-4d52-9b17-701d0dee79be" alt="Logo" width="200">
  
  <h1>Recharge Cards Management App</h1>
  
  <p>
    A comprehensive solution for managing recharge cards for service providers and customers
  </p>

  <!-- <div>
    <a href="#">
      <img src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white" height="60">
    </a>
    <a href="#">
      <img src="https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=app-store&logoColor=white" height="60">
    </a>
  </div>
</div> -->

## Overview
Crotty is a modern, feature-rich mobile application designed to simplify and streamline network card management and financial operations. It provides users with a seamless experience for buying, selling, and tracking network cards, as well as handling money transfers and reports. The app is built with scalability, security, and user-friendliness in mind.
## 📱 App Screenshots
  <td><img src="https://firebasestorage.googleapis.com/v0/b/weddinghallbooking-2ba28.appspot.com/o/protiflio_images%2Fcrotty_website-1.jpg?alt=media&token=b471e55a-46fe-4c9f-b541-9d37a7d909a4" alt="Image 2"></td>
  <td><img src="https://firebasestorage.googleapis.com/v0/b/weddinghallbooking-2ba28.appspot.com/o/protiflio_images%2Fcrotty_website-2.jpg?alt=media&token=d8454c02-b375-4675-aea1-b6fb32a084ad" alt="Image 2"></td>
  <td><img src="https://firebasestorage.googleapis.com/v0/b/weddinghallbooking-2ba28.appspot.com/o/protiflio_images%2Fcrotty_website-3.jpg?alt=media&token=312c4208-28a7-471c-96fd-1114cab16097" alt="Image 2"></td>
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



## 🧪 Testing
The project includes:
- Unit tests
- Widget tests
- Integration tests

## 📈 Performance Optimization
- Image caching
- Lazy loading
- Memory management
- Widget rebuilding optimization

## 🌍 Localization
- Arabic language support
- RTL layout support
- Dynamic locale switching

## 🛠️ Technology Stack
| Category | Technology |
|----------|------------|
| Framework | Flutter |
| State Management | BLoC Pattern |
| Backend Integration | Nodejs,Firebase |
| Cache Management | Redis,Hive |
| DataBase | MongoDB |
| UI/UX | Figma,Material Design, |
| Push Notifications | Firebase Cloud Messaging |
| Authentication | Backend Nodejs |


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
graph TD
    A[App Core] --> B[Features]
    A --> C[Core Services]
    A --> D[Config]
    
    B --> B1[Data Layer]
    B --> B2[Domain Layer]
    B --> B3[Presentation Layer]
    
    B3 --> E1[Views]
    B3 --> E2[BLoC]
    B3 --> E3[Components]
    
    C --> C1[Authentication]
    C --> C2[Navigation]
    C --> C3[Local Storage]
    
    D --> D1[Theme]
    D --> D2[Routes]
    D --> D3[Localization]
```


## 📱 Screen Architecture
```mermaid
flowchart LR
    A[Login] --> B[Home]
    B --> C[Network]
    B --> D[Cards]
    B --> E[Profile]
    B --> F[Reports]
```

---

<div align="center">
  <p>Built with ❤️ by Najeeb Aslan</p>
  <p>Copyright © 2022 Crotty. All rights reserved.</p>
</div>