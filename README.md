# 🌿 DHARA: The Ultimate Aqua–Hydro Manager 🌊🐟  
> **Smart. Sustainable. Self-Regulating.**  

**DHARA** (*Dynamic Hydro–Aqua Resource Automation*) is a next-generation **IoT-based hybrid farming system** that combines the best of **hydroponics and aquaponics** into a single, self-sustaining ecosystem.  
It automates water quality management, nutrient balancing, and environmental monitoring for both **fish and plants**, creating an intelligent, circular farming model designed for the future of sustainable agriculture. 🌱🐠⚙️  

---

## 🌍 Why DHARA?  

Modern agriculture depends heavily on water-intensive and chemical-based methods that harm soil and ecosystems.  
Hydroponics and aquaponics have emerged as cleaner alternatives, yet most systems work independently — focusing on either fish or plants.  

**DHARA** bridges this gap by integrating both ecosystems into a **single monitored loop** powered by **IoT automation**.  
It continuously tracks vital parameters, automatically maintains balance, and provides a **smart dashboard interface** for farmers to monitor, control, and optimize operations in real time. 💧📡  

---

## ✨ Key Features  

### 🧪 Hybrid Aquaponic–Hydroponic Ecosystem  
- Combines **fish farming (aquaponics)** and **soilless plant cultivation (hydroponics)**.  
- Fish waste enriches plant nutrients, while plants purify the water.  
- Enables a **closed-loop, sustainable cycle** requiring minimal manual intervention.  

---

### 📊 Real-Time IoT Monitoring (via Ubidots Dashboard)  
- Live tracking of:  
  - ⚗️ **pH Level**  
  - 🧪 **TDS (Total Dissolved Solids)**  
  - 🌫️ **Turbidity**  
  - 🌡️ **Temperature & Humidity**  
- Automatic alerts for abnormal readings.  
- User can set **custom min–max thresholds** for each parameter directly from the dashboard.  
- Data visualization through gauges, indicators, and real-time graphs.  

---

### ⚙️ Automated Pump Control (Relay Logic)  
- Four independent pumps controlled via a **4-channel relay module**:  
  1. **Acid Pump** – activates when pH > threshold  
  2. **Base Pump** – activates when pH < threshold  
  3. **Nutrient Pump** – triggers automatically every 12 hours for 30 seconds  
  4. **Drain Pump** – user-controlled via dashboard  
- Ensures water and nutrient balance with minimal human intervention.  

---

### 💧 Sustainable and Resource-Efficient Design  
- Up to **70% water savings** compared to soil farming.  
- No synthetic fertilizers — uses **organic nutrients** like Seaweed Extract, Worm Tea, and Iron Chelate.  
- Reuses fish waste to sustain plant growth.  
- Powered by a **5V portable power bank**, making it compact and energy efficient.  

---

## 💻 Technology Stack  

| Component | Description |
|------------|-------------|
| **Microcontrollers** | Arduino Uno (pH sensing) + ESP32 (IoT & Automation) |
| **Sensors** | pH, TDS, Turbidity, DHT11 (Temp & Humidity) |
| **Actuators** | 4-Channel Relay Module controlling acid, base, nutrient & drain pumps |
| **Display** | 16x2 I²C LCD for real-time readings |
| **Software** | Arduino IDE, ArduinoJson library |
| **IoT Platform** | Ubidots STEM Dashboard |
| **Power Supply** | 5V USB Power Bank |

---

## 🧭 Core Highlights  

- ✅ Hybrid Aqua–Hydro system supporting **user-defined fish–plant combinations**.  
- ✅ Automatic nutrient spraying and pH regulation.  
- ✅ Real-time dashboard monitoring and alert system.  
- ✅ Modular, compact, and scalable design.  
- ✅ Ideal for urban rooftop farming, academic research, and sustainable agri-labs.  

---

## 💡 Vision  

To create a future where **technology sustains nature** — where data-driven farming makes food production more efficient, clean, and accessible to everyone.  
DHARA empowers small-scale growers, students, and innovators to adopt **eco-intelligent automation** for sustainable farming. 🌍🌱  

---

## 🛠️ Future Upgrades  

- 🤖 **Machine Learning Integration:** Predictive maintenance and adaptive nutrient dosing.  
- 📱 **Mobile Application:** Real-time Android app for monitoring and control.  
- ☀️ **Solar Integration:** Full off-grid operation using renewable energy.  
- 🌊 **Expanded Sensor Suite:** Adding dissolved oxygen (DO) and EC sensors for deeper analysis.  

---

## 📷 Project Snapshots  

| Hybrid System Setup | DHARA Control Unit | IoT Dashboard |
|:-------------------:|:------------------:|:--------------:|
| ![Hybrid System Setup](https://github.com/tejashviraj19/DHARA-The_Ultimate_Aqua-Hydro_Manager/blob/main/Hybrid%20System%20Setup.png) | ![DHARA Control Unit](https://github.com/tejashviraj19/DHARA-The_Ultimate_Aqua-Hydro_Manager/blob/main/DHARA%20Control%20Unit.png) | ![IoT Dashboard](https://github.com/tejashviraj19/DHARA-The_Ultimate_Aqua-Hydro_Manager/blob/main/IoT%20Dashboard.png) |

---

## 🧩 System Overview  

**Sensor Inputs → Arduino (pH) + ESP32 (TDS, Temp, Humidity, Turbidity) → Relay Control → Pumps → Ubidots Dashboard (Monitor & Alerts)**  

---

## 📫 Connect  

💬 Have ideas, suggestions, or want to collaborate?  
Reach out via [LinkedIn](#https://www.linkedin.com/in/tejashvi-raj-918942251/) or open an issue on this repository — let’s build the future of sustainable farming together. 🌿🤝  

---

### 💚 Developed by:
**Tejashvi Raj**  
**Rishabh Kumar**  
**Karan Gandha**
