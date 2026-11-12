# 🚌 redBus Vikalp Pass
### A Universal, Same-Day Travel Pass for Short-Corridor Bus Routes

**A high-fidelity redBus prototype built with React Native and Expo | Team Vantage**

Vikalp Pass is a proposed ticketing solution for short-corridor intercity routes (under 250 km), developed as part of a case study by **Team Vantage**.

The concept reimagines traditional bus booking by allowing passengers to purchase a single universal travel pass instead of booking individual buses. Pass holders can board any eligible departure on their selected corridor within the validity period, subject to available capacity.

The prototype demonstrates the complete passenger journey, from route eligibility detection to pass generation and boarding verification.

---

## 📱 Download the Android APK

Experience the prototype directly on an Android device without setting up a development environment.

- 🚀 **[Download redBus Vikalp Pass APK](#)** — v1.0.0
- 📦 **[View GitHub Releases](#)** — v1.0.0

> Download the APK, install it on your Android device, and explore the complete Vikalp Pass experience.

### Installation Guide

1. Open the APK download link on your Android smartphone or tablet.
2. Download `redBus-Vikalp-Pass.apk`.
3. Open the downloaded file from your notifications or Downloads folder.
4. Allow installation from unknown sources if Android prompts you.
5. Install and launch the application.

---

## 💡 The Concept: Vikalp Pass

Traditional bus booking requires passengers to select a specific bus and departure time, even when travelling on frequently serviced short-distance routes.

Vikalp Pass introduces a more flexible alternative:

- Book a corridor instead of an individual bus.
- Access multiple eligible departures using one pass.
- Travel on the same day without committing to a fixed departure.
- Benefit from a discounted fare compared to the assured-ticket benchmark.

**One corridor. Multiple departures. One universal pass.**

---

## ✨ Key Features

### 1. Short-Corridor Distance Engine
- Automatically identifies eligible intercity routes under 250 km.
- Activates Vikalp Pass eligibility for qualifying corridors.
- Demonstrates the Pune ⇄ Mumbai route as an example (148 km Expressway Corridor).

### 2. Strict Same-Day Travel Policy
- Vikalp Pass is available exclusively for travel on the current date.
- Selecting a future journey date automatically disables pass eligibility.
- The app reverts to the standard bus search experience for future-date bookings.

This restriction ensures that the pass is designed around perishable, unbooked seat inventory rather than advance reservations.

### 3. 24-Hour Departure Timetable
- Displays scheduled departures over the next 24 hours.
- Includes estimated arrival times.
- Shows indicative spare-capacity estimates.
- Provides a unified view of eligible buses without requiring individual bookings.

*The timetable is informational and non-clickable in this prototype.*

### 4. Universal Pass & Dummy Payment
- Implements a flat-rate corridor pass.
- Demonstrates a 10% discounted fare:
  - Regular assured-ticket benchmark: ₹450
  - Vikalp Pass price: ₹405
- Includes a simulated payment flow.
- Generates a universal digital boarding pass after successful simulated payment.

### 5. Digital QR Boarding Pass
- High-resolution vector QR code.
- Unique PNR generation.
- Countdown timer indicating remaining pass validity.
- Designed to represent a digital ticket that can be presented during boarding.

### 6. Smart Departure Filtering
Passengers can filter scheduled departures by:

- **All Departures** – View every eligible departure.
- **AC Only** – Air-conditioned buses.
- **Non AC** – Non-air-conditioned buses.
- **Electric Express** – Electric bus departures.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React Native | Cross-platform mobile application |
| Expo | Development and Android builds |
| JavaScript | Application logic |
| QR Code Generation | Digital boarding pass |
| Vector Graphics | High-resolution QR and pass visuals |

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm
- Expo CLI / Expo tooling
- Android Studio or an Android device (for testing)

### Installation

Clone the repository:

```bash
git clone <YOUR_REPOSITORY_URL>
```

Navigate to the project directory:

```bash
cd redbus-vikalp-pass
```

Install dependencies:

```bash
npm install
```

Start the Expo development server:

```bash
npx expo start
```

Run on Android:

```bash
npx expo start --android
```

---

## 📂 Project Scope

This project is a **functional case study prototype**, designed to demonstrate the proposed Vikalp Pass user experience.

| Component | Implementation |
|---|---|
| Route eligibility | Implemented |
| Distance-based activation | Implemented |
| Same-day restriction | Implemented |
| Departure timetable | Implemented |
| Spare-capacity estimates | Demonstration data |
| Payment gateway | Simulated |
| Universal QR pass | Implemented |
| PNR generation | Implemented |
| Departure category filters | Implemented |

**Important:** This is an independent prototype, not an official redBus application. It uses demonstration data and simulated payment functionality. It is not connected to redBus's production booking, inventory, payment, or ticket-validation systems.

---

## 👥 Team

**Team Vantage**

Developed as part of a product case study exploring improvements to the intercity bus booking experience.

---

## 🎯 Our Vision

We believe passengers travelling short distances should have more flexibility in how they commute.

Vikalp Pass explores a different approach to bus ticketing: moving from booking a specific departure to booking access to a travel corridor.

**Less planning. More flexibility. One pass, multiple possibilities.**

---

*Built with ❤️ by Team Vantage.*
