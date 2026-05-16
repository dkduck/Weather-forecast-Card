# 🌤️ MET.CO Weather Cards for Home Assistant
*A clean and visual way to display MET.CO forecast data inside Home Assistant*

This repository contains my custom setup for presenting weather data from the **MET.CO integration** in Home Assistant.  
It includes three cards that provide both short‑term and long‑term forecasts in a clear and visually appealing format.

---

## ✨ Features
- **5‑Day Forecast Card** – Overview of the next five days  
- **5‑Hour Forecast Card** – Hour‑by‑hour details for the next five hours  
- **Combined Forecast Card** – Switch between daily and hourly view in one card  

---

## 🖼️ Visual Examples

### 5‑Day Forecast  
![5-Day Forecast](images/5-day-forecast.png)

### 5‑Hour Forecast  
![5-Hour Forecast](images/5-hour-forecast.png)

### Combined Card  
![Combined Forecast Card](images/combined-forecast.png)

---

## ⚙️ Requirements

To use these weather cards in Home Assistant, the following components must be installed:

# Integration
Met.no (built‑in weather provider used by MET.CO)

# Cards
- vertical-stack (core Lovelace card) &
- custom:button-card (HACS custom card)

# input_boolean

Navn: vejr_visning

---

## 🧩 How It Works
All cards are powered by:

- The **MET.CO integration**  
- **Daily** and **hourly** forecast entities  
- A layout optimized for **Sections View**  
- A clean structure that highlights the most important weather details  

---

## 🚀 Purpose
This project demonstrates how MET.CO forecast data can be displayed in a **clear**, **functional**, and **dashboard‑friendly** way.  
Use it as inspiration or integrate it directly into your own Home Assistant setup.
