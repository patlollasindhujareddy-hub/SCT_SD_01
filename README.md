# SCT_SD_01
A C-based temperature conversion utility that converts values between Celsius, Fahrenheit, and Kelvin scales. Built for Task 01 of the SkillCraft Technology internship.
# Temperature Converter (C Implementation)

## 📌 Project Overview
This is a command-line utility written in **C** that converts temperatures between the **Celsius**, **Fahrenheit**, and **Kelvin** scales. 

Developed as **Task 01** during my internship at **SkillCraft Technology**, this project focuses on fundamental C programming concepts, including:
- Standard Input/Output (`scanf` and `printf`)
- Conditional control flow (`switch-case` and `if-else` blocks)
- Precision floating-point arithmetic (`float` or `double`)

## 🚀 Features
- **Multi-scale Conversion:** Convert seamlessly between Celsius (°C), Fahrenheit (°F), and Kelvin (K).
- **Interactive Menu:** Simple, clean console interface for user input.
- **Accurate Precision:** Handles decimal temperature values accurately.

## 🧮 Formulas Implemented
- **Celsius to Fahrenheit:** $F = (C \times \frac{9}{5}) + 32$
- **Celsius to Kelvin:** $K = C + 273.15$
- **Fahrenheit to Celsius:** $C = (F - 32) \times \frac{5}{9}$
- **Kelvin to Celsius:** $C = K - 273.15$

## 🛠️ How to Compile and Run
To run this program locally on your machine, open your terminal and use a C compiler like `gcc`:

```bash
# Compile the program
gcc temperature_converter.c -o converter

# Run the executable
./converter
