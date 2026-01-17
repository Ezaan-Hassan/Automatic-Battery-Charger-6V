# Automatic Battery Charger with Auto Cut-Off

## 🔋 Project Overview
An analog automatic battery charger designed for 6V 4.5Ah sealed lead-acid batteries with voltage-based auto cut-off and LED indication.

## ✨ Key Features
- ✅ Automatic charging cutoff at 6.9V
- ✅ Safe C/10 charging rate (450mA)
- ✅ Red and Green LED for charging indication
- ✅ Current limiting (15Ω 5W resistor)
- ✅ No microcontroller - pure analog design
- ✅ Uses LM358 comparator for voltage sensing

## 👥 Team - Circuit Breakers
- Ezaan Hassan
- Ashama Abbasi
- Abdullah Ali
- Kazim Hussain

## 🛠️ Components Used
| Component | Value/Rating | Quantity |
|-----------|--------------|----------|
| Transformer | 230V/12V, 500mA | 1 |
| Bridge Rectifier | W10M | 1 |
| Filter Capacitor | 3300µF, 50V | 1 |
| Voltage Regulator | LM7812 | 1 |
| Comparator IC | LM358 | 1 |
| Power Transistor | TIP41C | 1 |
| Zener Diode | 6.2V, 1W | 1 |
| Current Limiter | 15Ω, 5W | 1 |
| Resistors | Various (1kΩ, 10kΩ, 4.7kΩ) | - |
| LED | 5mm Red & Green | 1 |

## 📐 Circuit Specifications
- **Input:** 230V AC, 50Hz
- **Output:** 6.9V charging voltage
- **Charging Current:** 350-450mA (C/10 rate)
- **Cutoff Voltage:** 6.9V (automatic)
- **Charging Time:** 10-14 hours (full discharge)
- **Battery Type:** 6V 4.5Ah SLA

## 📊 Circuit Diagram
![Circuit Diagram](Circuit-Diagrams/complete-circuit-diagram.png)

## 🔬 How It Works
1. **Power Supply:** Converts 230V AC → 12V DC
2. **Reference Circuit:** Creates stable 3.45V threshold
3. **Voltage Sensing:** Monitors battery voltage continuously
4. **Comparator:** Compares battery voltage with threshold
5. **Auto Cutoff:** Stops charging at 6.9V (full charge)
6. **LED Indicator:** Red = Charging, Off = Fully Charged

## 📁 Documentation
- [📄 Complete Project Report](Documentation/Project-Report.pdf)
- [📄 Component List with Prices](Documentation/Component-List.pdf)
- [📄 Design Calculations](Documentation/Calculations.pdf)

## 🎯 Applications
- UPS battery charging
- Emergency lighting systems
- Solar power storage
- Portable power banks
- Electric toy vehicles

## 📸 Project Photos

### Assembled Circuit
![Assembled Circuit](Photos/assembled-circuit.jpg)

## 📞 Contact
For questions or collaboration:
- **LinkedIn:** 
- **Email:** ezaanhassan1@gmail.com

---

⭐ **If you found this project helpful, please give it a star!**

**Made with ❤️ by Team Circuit Breakers**
```
