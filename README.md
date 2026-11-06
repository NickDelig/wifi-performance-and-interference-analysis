# 📡 Wi-Fi Networks: Performance, Signal Strength, and Interference Analysis

This repository contains a comprehensive experimental study of wireless networks (Wi-Fi) conducted in a real-world residential environment. The project was developed for the Department of Informatics at the School of Information Sciences & Technology, Athens University of Economics and Business (AUEB).

The research is divided into three main parts, examining the effects of distance, physical obstacles, and interference on the quality of wireless communication.

## 📂 Project Contents

### Part A: Wireless Network Signal Strength and Distribution
* Examination of received signal strength (RSSI) attenuation in relation to the distance from the Access Point and the presence of internal walls.
* Recording of available networks in both the 2.4 GHz and 5 GHz frequency bands.
* Classification of detected networks into signal power categories (Strong: > -60 dBm, Moderate: -70 to -60 dBm, Weak: < -70 dBm).
* Evaluation of the time variability of the wireless signal over consecutive measurements.

### Part B: Link Speed Dependence on Signal Strength (RSSI) and Obstacles
* Study of the correlation between the received signal strength and the Wi-Fi Link Speed.
* Analysis of the Adaptive Modulation and Coding (AMC) mechanism and Rate Fallback due to low Signal-to-Noise Ratio (SNR).
* Comparative performance analysis between two different receivers: a Smartphone (supporting Wi-Fi 5) and a Laptop (equipped with an Intel Wi-Fi 6 AX201, 2x2 MIMO network card).
* Examination of technical factors causing performance discrepancies, such as antenna design, Spatial Diversity, and power management.

### Part C: Interference Analysis and Optimal Channel Selection
* Identification of interference from neighboring apartment networks on both 2.4 GHz and 5 GHz bands.
* Logging of BSSIDs, transmission channels, and RSSI to analyze co-channel interference.
* Recommendations for selecting the optimal channel to improve reception, such as switching to channel 1 for the 2.4 GHz band and remaining on channel 44 for the 5 GHz band.

## 🛠️ Equipment & Software
The experimental measurements were conducted using the following equipment:
* **Software:** WiFi Analyzer (open-source edition by VREM).
* **Measurement Devices:**
  * Smartphone Xiaomi Redmi Note 11 (Android 13).
  * Laptop Lenovo ThinkPad L14.
* **Access Point (AP):** A mobile phone operating in Mobile Hotspot mode, placed in a fixed location (living room).

## 📊 Results
Detailed graphs illustrating Link Speed vs. RSSI, measurement tables, and the corresponding spectrum analyzer screenshots are included in the PDF files within this repository.
