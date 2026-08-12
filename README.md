# 🧊 Opti Fridge 
**Save Food, Save Energy, Feed the Community.**

![Opti Fridge Banner](https://placehold.co/1000x300/4CAF50/FFFFFF?text=Opti+Fridge+-+Food+%26+Energy+Waste+Reduction)


## 🌍 The Problem
Refrigerators in campus cafeterias, restaurants, and bakeries are massive consumers of electricity. Unfortunately, a huge portion of that energy is wasted cooling food that eventually expires and gets thrown away. While students and local communities face food insecurity, edible food sits in commercial fridges past its prime. This creates a double-negative environmental impact: greenhouse gases from rotting food in landfills, and wasted electricity from cooling doomed inventory.

## 💡 The Solution: Opti Fridge
**Opti Fridge** is a real-time web platform that connects surplus refrigerated food with people who need it *before* it expires. By tracking the shelf-life of refrigerated items, the platform automatically alerts users to available surplus food, coordinates pickups, and tracks the exact amount of electricity saved by not cooling expired food. 

## ✨ Key Features

*   **⏱️ Expiration-Driven Alerts:** Automated tracking of refrigerated items. When food nears its expiration date, it is automatically listed for discounted sale or donation.
*   **⚡ Energy Impact Dashboard:** A unique analytics view that calculates the kilowatt-hours (kWh) of electricity saved by clearing out surplus food, alongside traditional metrics like meals saved and CO2 diverted.
*   **📍 Real-Time Geolocation Matching:** Users can browse an interactive map to see nearby available fridge surplus, filtered by dietary preferences (vegan, gluten-free, etc.).
*   **📅 Smart Pickup Scheduling:** Time-slotted reservation system to ensure smooth logistics for businesses and prevent overcrowding.
*   **📱 Instant Notifications:** SMS and push notifications alert nearby students or community members the second surplus food is listed.
*   **🤝 Trust & Rating System:** Accountability metrics for both donors (ensuring food safety/quality) and recipients (ensuring they show up for claimed food).

## 🛠️ Tech Stack

| Component | Technology |
| :--- | :--- |
| **Frontend** | React, HTML, CSS, JavaScript |
| **Backend** | Node.js, Express |
| **Database** | MongoDB |
| **APIs** | Geolocation API, Push Notifications, Twilio (SMS) |
| **Payments** | Stripe (for optional donations to food rescue) |

## 🚀 Getting Started

### Prerequisites
*   Node.js (v14 or higher)
*   MongoDB installed and running locally or via MongoDB Atlas
*   API Keys for Twilio and Google Maps/Geolocation

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/opti-fridge.git](https://github.com/yourusername/opti-fridge.git)
