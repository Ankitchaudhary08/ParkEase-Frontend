# ParkEase Frontend

This is the frontend application for **ParkEase**, a modern parking management system. Built with **Angular**, it provides a seamless user experience for drivers to find and book parking spots, and for administrators/managers to manage parking facilities.

## 🚀 Features

-   **Interactive Map**: Locate parking lots near you.
-   **Real-time Availability**: View live status of parking spots.
-   **Secure Booking**: Book spots and pay via Razorpay integration.
-   **User Dashboard**: Manage your profile, bookings, and vehicles.
-   **Admin/Manager Panel**: Comprehensive tools for lot and spot management.

## 🛠️ Tech Stack

-   **Framework**: Angular 21
-   **Styling**: Angular Material / CSS
-   **Map**: Leaflet
-   **State Management**: RxJS
-   **Communication**: REST API (via Backend Gateway)

## 📦 Getting Started

### Prerequisites

-   Node.js (v24.x recommended)
-   NPM

### Installation

1.  Navigate to the directory:
    ```bash
    cd parkease-frontend
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```

### Running Locally

To start the development server with the proxy configuration for the backend:

```bash
npm start
```

The application will be available at `http://localhost:4200`.

## 🏗️ Architecture

The frontend communicates with a microservices-based backend through an **API Gateway** on port `8080`. Authentication is handled via **JWT** stored in the browser's local storage.

---

© 2026 ParkEase System. All rights reserved.
