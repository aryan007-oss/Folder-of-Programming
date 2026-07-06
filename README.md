# Temperature_calculator

# Temperature Conversion Utility

A lightweight, modular Python utility designed to convert temperature values seamlessly between **Celcius**, **Fahrenheit**, and **Kelvin**. This repository provides both a reusable script backend and a Jupyter Notebook scratchpad for interactive testing.

---

## 🛠️ Components

* **`temperature.py`** : The core utility script containing highly optimized functional blocks for basic and advanced temperature scale transitions.
* **`temp.ipynb`** : A clean, empty Jupyter Notebook workspace prepared for interactive execution, testing, or quick prototyping using the script functions.


  ## 🚀 Features & Core Functions

The utility exposes the following transformation functions inside `temperature.py`:

| Target Scale | Source Scale | Function Name |
| :--- | :--- | :--- |
| **Celcius** | Fahrenheit | `fahrenheit_to_celcius(fahrenheit)` |
| **Celcius** | Kelvin | `kelvin_to_celcius(kelvin)` |
| **Fahrenheit** | Celcius | `celcius_to_fahrenheit(celcius)` |
| **Fahrenheit** | Kelvin | `kelvin_to_fahrenheit(kelvin)` |
| **Kelvin** | Celcius | `celcius_to_kelvin(celcius)` |
| **Kelvin** | Fahrenheit | `fahrenheit_to_kelvin(fahrenheit)` |

> 📌 **Note:** The script also includes a generic `celcius(temperature)` alias mapping Fahrenheit inputs directly to Celsius values.

---

## 💻 Quick Start & Usage

You can easily import these functions into your own Python programs or within the provided notebook:

```python
from temperature import celcius_to_fahrenheit, fahrenheit_to_kelvin

# Convert 25°C to Fahrenheit
f_temp = celcius_to_fahrenheit(25)
print(f"{f_temp}°F")  # Output: 77.0°F

# Convert 98.6°F to Kelvin
k_temp = fahrenheit_to_kelvin(98.6)
print(f"{k_temp} K")  # Output: 310.15 K
