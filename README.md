# Fuzzy Irrigation System (Java)

## Description
This project implements a fuzzy logic-based irrigation system that determines the optimal amount of water required for crops based on environmental conditions. 

The system uses soil moisture, temperature, and humidity as input parameters and applies fuzzy inference rules to compute the recommended irrigation level in liters per square meter.

---

## Features
- Fuzzy logic-based decision making
- Rule-based inference system
- Environmental parameter analysis (soil moisture, temperature, humidity)
- Defuzzification to produce real-world output
- Lightweight and easy to run

---

## Technologies Used
- Java
- Fuzzy Logic (Artificial Intelligence concept)

---

## How It Works
1. **Fuzzification**  
   Converts input values into fuzzy sets such as dry, medium, and wet for soil moisture; cold, moderate, and hot for temperature; and low, medium, and high for humidity.

2. **Rule Evaluation**  
   Applies predefined IF-THEN rules to determine irrigation levels.

3. **Aggregation**  
   Combines the results of all rules into output categories (low, medium, high).

4. **Defuzzification**  
   Converts fuzzy output into a precise irrigation value (liters/m²).

---

## Example Input
- Soil Moisture: 35%
- Temperature: 28°C
- Humidity: 30%

## Example Output
Recommended irrigation (liters/m²): 4.73

---

## How to Run

1. Compile the program:
   ```bash
   javac FuzzyIrrigation.java
