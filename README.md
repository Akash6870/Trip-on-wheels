# 🚐 Trip on Wheels — Tourist Vehicle Pre-Booking & Price Aggregator Platform

> A full-stack web application for pre-booking commercial group tourist vehicles (Tempo Travellers, Mini Buses, Volvo Coaches, and SUVs) with dynamic fare calculation, multi-tier user roles, fleet management, and admin approval workflows.

---

## 📌 Project Overview

Unlike regular point-to-point ride-hailing apps (e.g., Uber/Ola), outstation group transport requires multi-variable pricing models and extended driver coordination. **Trip on wheels** addresses this fragmented market by connecting group travellers directly with verified fleet owners.

Users can compare transparent pricing breakdowns across vehicle segments, book outstation routes, and receive instant digital receipts, while fleet operators can manage their listings and track earnings.

---

## ✨ Key Features

### 👤 Renter / Passenger Experience
* **Smart Search & Filters:** Search by origin, destination, travel dates, and vehicle segment (Sedan/SUV, Tempo Traveller, Mini Bus, Luxury Volvo).
* **Transparent Pricing Engine:** Real-time breakdown including base per-km rates, driver daily allowances, and minimum distance thresholds.
* **Filter by Amenities:** Refine listings by Pushback Recliners, AC/Non-AC, Luggage Space, Audio/Video systems, and Ambient Lighting.
* **Instant Booking Flow:** Complete booking details, passenger counts, pickup location, and download a digital tax receipt.
* **My Bookings Dashboard:** View live booking statuses (Confirmed, Pending, Completed) and manage trip details.

### 🚍 Fleet Operator / Partner Portal
* **Vehicle Onboarding:** Upload vehicle listings with multi-angle photos, seating capacity, base rates, and daily driver allowance rules.
* **Document Verification:** Submit commercial RC, Tourist Permit, Insurance, and Driving License for platform compliance.
* **Earnings & Analytics:** Monitor total trips, driver assignments, and active bookings.

### 🛡️ Admin Verification Hub
* **Listing Moderation:** Review and verify incoming vehicle listings and operator credentials before publishing to the public catalog.
* **Platform Overview:** Track active fleet metrics, user bookings, and system-wide revenue.

---

## 📊 Fare Calculation Formula

The platform uses realistic commercial outstation transport pricing logic:

$$\text{Total Fare} = \max(\text{Trip Distance} \times \text{Per KM Rate}, \text{Min KM Per Day}) + (\text{Driver Allowance} \times \text{Days}) + \text{Tolls/Permits}$$

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, Tailwind CSS (CDN), JavaScript (ES6+)
* **UI Components:** Lucide Icons, Inter Font
* **Architecture:** Single-Page Application (SPA) with responsive design and interactive state management

---

## 🚀 Getting Started

### Prerequisites
All you need is a modern web browser (Chrome, Firefox, Edge, Safari). No dependencies, Node package installs, or server configurations are required.

### Local Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/tour-ride-web-app.git](https://github.com/YOUR_USERNAME/tour-ride-web-app.git)
