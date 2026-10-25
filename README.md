# 🚗 QuickPark – Smart Parking Discovery & Booking App

QuickPark is a Flutter-based mobile application project designed to simplify parking discovery and booking. It provides a user-friendly interface to explore parking locations, view parking details, select parking slots, manage vehicles, and track sample bookings.

## ✨ Features

- 🔐 **Login & Sign Up** – Demo authentication interface
- 🅿️ **Parking Discovery** – Browse sample parking locations
- 🔎 **Search & Explore** – Find parking options and explore available places
- 📍 **Parking Details** – View location details, prices, and facilities
- 🎯 **Slot Selection** – Select a parking slot from the available slot layout
- 📅 **Booking Management** – Choose a date, start time, and end time
- 🚘 **Vehicle Management** – Add, edit, and delete vehicles
- 🧾 **Booking History** – View booking details and cancel sample bookings
- 👤 **Profile Management** – Edit profile information
- 🧭 **Directions Demo** – Explore a sample directions screen
- 📱 **Material Design UI** – Clean interface with bottom navigation

## 🛠️ Technology Stack

- **Framework:** Flutter
- **Language:** Dart
- **UI:** Flutter Material Design
- **IDE / Platform:** FlutLab.io
- **Dependencies:** Flutter SDK; no additional runtime packages are declared

## 📂 Project Structure

```text
Quickpark/
├── android/                  # Android platform configuration
├── ios/                      # iOS platform configuration
├── web/                      # Web app files and icons
├── lib/
│   └── main.dart             # Main QuickPark application code
├── test/                     # Flutter test directory
├── pubspec.yaml              # Project configuration and dependencies
├── analysis_options.yaml     # Dart analysis settings
├── .metadata                 # Flutter project metadata
└── README.md                 # Project documentation
```

## 🚀 Getting Started

### Run using FlutLab.io

1. Download or clone this repository.
2. Open [FlutLab.io](https://flutlab.io/).
3. Import or open the Flutter project.
4. Wait for the project dependencies to resolve.
5. Open `lib/main.dart` and run the application.

### Run locally

Make sure Flutter is installed, then run these commands from the project directory:

```bash
flutter pub get
flutter run
```

## 🅿️ How to Use

1. Open QuickPark and enter demo login details.
2. Explore the sample parking locations.
3. Select a parking place to view its details.
4. Choose a parking slot, vehicle, booking date, and time.
5. Review and confirm the sample booking.
6. View or manage bookings from the **Bookings** tab.
7. Add or manage vehicles from the **Vehicles** tab.
8. Update your profile from the **Profile** tab.

## 🎯 Project Objective

The main objective of QuickPark is to demonstrate a convenient parking discovery and booking workflow using Flutter. The project focuses on mobile UI design, navigation between screens, form handling, slot selection, and basic booking-state management.

## ⚠️ Current Limitations

- Parking locations, prices, and availability are sample data.
- Login and sign-up are demo interfaces, not server-based authentication.
- Booking and vehicle information is stored in application memory and is not permanently saved.
- The directions screen is a demo; live GPS navigation and interactive maps are not integrated.
- Real-time parking updates, online payments, and backend/database integration are not implemented.

## 🔮 Future Enhancements

- Integrate Google Maps and live GPS navigation.
- Add backend and database support for persistent user accounts and bookings.
- Implement real-time parking slot availability.
- Integrate secure authentication.
- Add online payments and digital receipts.
- Send booking confirmations and reminders.

## 🎓 Project Information

- **Project Name:** QuickPark
- **Project Type:** Flutter Mobile Application
- **Category:** Smart Parking / UI Design Lab
- **Development Environment:** FlutLab.io

---

**QuickPark — Find your spot. Park with confidence.** 🚗
