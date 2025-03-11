# Soil Health Monitoring System 🌱  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  

## 📖 About the Project  
A real-time IoT-based system to monitor soil health parameters (NPK, moisture, temperature) and detect pesticides. Data is secured using blockchain to ensure tamper-proof storage.  

### 🔍 Features  
- Real-time soil parameter monitoring.  
- Pesticide detection alerts for farmers.  
- Blockchain-based data integrity.  
- Raspberry Pi 3 as the central processing unit.  

### 🛠️ Hardware Components  
- **Raspberry Pi 3** (central controller)  
- NPK, moisture, and temperature sensors  
- Raspberry Pi camera (for visual soil analysis)  
- CSI/HDMI cables (camera and display connectivity)  
- Power supplies for all components  

### 🎥 Project Demo  
- [Video Demo Link](#) *(add a YouTube/Google Drive link here)*  
- Video timestamps: `00:00` - System overview, `00:30` - Sensor data collection demo.  

---

## 🔄 Data Flow Using Blockchain  
1. Sensors collect soil data.  
2. Raspberry Pi processes and encrypts the data.  
3. Data is stored in a blockchain network (e.g., Hyperledger/ETH) for security.  
4. Farmers receive alerts via SMS/mobile app if pesticides are detected.  

---

## 📂 Block Diagram  
![Block Diagram](blockdiagram.png) *(upload your diagram image to GitHub and link it here)*  

### Block Diagram Description:  
- **Sensors**: NPK, moisture, temperature.  
- **Raspberry Pi 3**: Aggregates data, triggers alerts.  
- **Camera**: Captures soil images via CSI cable.  
- **Blockchain Node**: Laptop or external server for storing encrypted data.  
- **Farmer Alert System**: SMS/email notifications.  

---

## 🚀 Installation  
1. Clone the repository:  
   ```bash  
   
