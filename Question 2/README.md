# Temperature Converter (Fahrenheit to Celsius)

A simple Python script that takes a temperature in Fahrenheit, converts it to Celsius, and evaluates whether the temperature is hot or cold.

## How It Works
When executed, the program performs the following steps:
1. **Input:** Prompts the user to enter a temperature value in Fahrenheit.
2. **Conversion:** Uses a custom function to calculate the equivalent temperature in Celsius using the standard formula: `celsius = (5/9) * (fahrenheit - 32)`.
3. **Output:** Displays the converted Celsius value.
4. **Evaluation:** Checks the Celsius temperature against a threshold of 20 degrees:
   * If it is greater than 20°C, it prints **"ITS HOT HERE"**.
   * If it is 20°C or below, it prints **"IT’S COLD HERE"**.
