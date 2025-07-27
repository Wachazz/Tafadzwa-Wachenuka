# 👨‍🔧 TAFADZWA WACHENUKA  
**Electronics Engineer | AgriTech Innovator | Renewable Energy Specialist**  

⚡ **Bridging hardware and data science for**  
🌱 Precision Agriculture | 🌞 Solar Tech | 🤖 Robotics | 📡 Smart Grids  

---

## 🛠️ **Technical Stack**  
<div align="center" style="display: flex; flex-wrap: wrap; gap: 8px; justify-content: center;">

**Embedded & IoT**  
![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?logo=c%2B%2B)
![STM32](https://img.shields.io/badge/STM32-03234B?logo=stmicroelectronics)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?logo=espressif)

**Data & AI**  
![Python](https://img.shields.io/badge/Python-3776AB?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow)

**AgriTech**  
![LoRa](https://img.shields.io/badge/LoRaWAN-9999FF?logo=lorawan)
![GIS](https://img.shields.io/badge/GIS-3D9970?logo=qgis)
![Dronecode](https://img.shields.io/badge/Drone_Tech-21759B?logo=drones)

</div>

---

## 🌱 **Data-Driven AgriTech Projects**  

### 1. **Smart Irrigation System**  
*IoT-enabled soil monitoring with predictive analytics*  
```python
# Soil moisture prediction model
from sklearn.ensemble import RandomForestRegressor
import pandas as pd

data = pd.read_csv('sensor_data.csv')
X = data[['temp', 'humidity', 'historical_usage']]
y = data['irrigation_needed']

model = RandomForestRegressor()
model.fit(X, y)  # Deployed to ESP32 via TensorFlow Lite
