# 📡 Wi-Fi Networks: Performance, Signal Strength, and Interference Analysis

This repository contains a comprehensive experimental study of wireless networks (Wi-Fi) conducted in a real-world residential environment[cite: 1]. The project was developed for the Department of Informatics at the School of Information Sciences & Technology, Athens University of Economics and Business (AUEB)[cite: 1, 8, 12].

The research is divided into three main parts, examining the effects of distance, physical obstacles, and interference on the quality of wireless communication[cite: 1, 8, 12].

## 📂 Project Contents

### Part A: Wireless Network Signal Strength and Distribution
* Examination of received signal strength (RSSI) attenuation in relation to the distance from the Access Point and the presence of internal walls[cite: 1, 3, 4].
* Recording of available networks in both the 2.4 GHz and 5 GHz frequency bands[cite: 1].
* Classification of detected networks into signal power categories (Strong: > -60 dBm, Moderate: -70 to -60 dBm, Weak: < -70 dBm)[cite: 2].
* Evaluation of the time variability of the wireless signal over consecutive measurements[cite: 2, 4].

### Part B: Link Speed Dependence on Signal Strength (RSSI) and Obstacles
* Study of the correlation between the received signal strength and the Wi-Fi Link Speed[cite: 9].
* Analysis of the Adaptive Modulation and Coding (AMC) mechanism and Rate Fallback due to low Signal-to-Noise Ratio (SNR)[cite: 9, 10].
* Comparative performance analysis between two different receivers: a Smartphone (supporting Wi-Fi 5) and a Laptop (equipped with an Intel Wi-Fi 6 AX201, 2x2 MIMO network card)[cite: 8, 10].
* Examination of technical factors causing performance discrepancies, such as antenna design, Spatial Diversity, and power management[cite: 10, 11].

### Part C: Interference Analysis and Optimal Channel Selection
* Identification of interference from neighboring apartment networks on both 2.4 GHz and 5 GHz bands[cite: 13, 14].
* Logging of BSSIDs, transmission channels, and RSSI to analyze co-channel interference[cite: 12, 14].
* Recommendations for selecting the optimal channel to improve reception, such as switching to channel 1 for the 2.4 GHz band and remaining on channel 44 for the 5 GHz band[cite: 14, 15].

## 🛠️ Equipment & Software
The experimental measurements were conducted using the following equipment:
* **Software:** WiFi Analyzer (open-source edition by VREM)[cite: 1].
* **Measurement Devices:**
  * Smartphone Xiaomi Redmi Note 11 (Android 13)[cite: 1, 8].
  * Laptop Lenovo ThinkPad L14[cite: 8].
* **Access Point (AP):** A mobile phone operating in Mobile Hotspot mode, placed in a fixed location (living room)[cite: 1, 8, 12].

## 📊 Results
Detailed graphs illustrating Link Speed vs. RSSI, measurement tables, and the corresponding spectrum analyzer screenshots are included in the PDF files within this repository.
