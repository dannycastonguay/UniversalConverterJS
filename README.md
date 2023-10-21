# UniversalConverterJS

A comprehensive JavaScript library for unit, currency, and other conversions, optimized for web applications.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Directory Structure](#directory-structure)
- [Contribution](#contribution)
- [License](#license)

## Introduction

UniversalConverterJS is designed to simplify unit, currency, and other conversions. Optimized for web applications.

## Features

### Math and Science
- Length (meters, centimeters, miles, etc.)
- Mass (kilograms, pounds, ounces, etc.)
- Time (seconds, minutes, hours, etc.)
- Temperature (Celsius, Fahrenheit, Kelvin)
- Area (square meters, acres, square feet, etc.)
- Volume (liters, gallons, cubic meters, etc.)
- Velocity (meters per second, miles per hour, etc.)
- Acceleration (m/s^2, ft/s^2, etc.)
- Energy (joules, calories, BTU, etc.)
- Force (newtons, pounds-force, etc.)
- Pressure (pascals, bar, psi, etc.)

### Engineering
- Electrical Resistance (ohms)
- Electrical Conductance (siemens)
- Electrical Voltage (volts)
- Electrical Current (amperes)
- Power (watts, horsepower, etc.)
- Magnetic Field (tesla, gauss)
- Luminance (candela, lumens)
- Frequency (hertz, RPM)
- Bits and Bytes (byte, kilobyte, megabyte, etc.)

### Art
- Resolution (dpi, ppi)
- Paper Sizes (A4, letter, etc.)
- Aspect Ratios (4:3, 16:9, etc.)

### Business
- Currency (USD, EUR, SGD, etc.)
- Interest Rates (APR, APY)
- Time (fiscal years, quarters, etc.)
- Market Cap (million, billion, etc.)
- Units Sold (single, dozen, gross, etc.)
- Data Size (MB, GB, TB, etc.)

### General
- Angles (degrees, radians, gradians)
- Cooking Units (teaspoons, tablespoons, cups, etc.)

### Medicine and Biology
- Concentration (moles per liter, parts per million)
- Blood Sugar Level (mg/dL, mmol/L)
- Dosage (milligrams, micrograms)
- Enzyme Units (Katal, international unit)

### Sports and Fitness
- Distance (miles, kilometers)
- Speed (kph, mph)
- Weight (kg, lb)
- Caloric Energy (calories, kilojoules)

### Textiles and Fashion
- Yarn Count (tex, denier)
- Fabric Weight (GSM, ounces per square yard)

### Photography
- Exposure Value (EV)
- Focal Length (mm)

### Geography
- Geographic Coordinates (degrees, minutes, and seconds; decimal)
- Altitude (meters, feet)

### Aviation and Marine
- Altitude (feet, meters)
- Speed (knots, mph, m/s)
- Fuel Efficiency (miles per gallon, liters per 100km)

### Chemistry and Material Science
- Molarity (moles per liter)
- Density (grams per cm³, kg per m³)
- Hardness (Mohs, Vickers)
- Electrical Resistivity (ohm meters)

### Computing
- Processing Speed (MIPS, FLOPS)
- Bandwidth (bps, Mbps, Gbps)

### Environmental Science
- Rainfall (inches, mm)
- Air Quality Index (AQI, PM2.5, PM10)

### Music
- Frequency (Hz, kHz)
- Tempo (BPM)

### Real Estate
- Area (square feet, square meters)
- Price per Square Foot/Meter

### Automotive
- Fuel Efficiency (miles per gallon, liters per 100 km)
- Torque (newton-meters, foot-pounds)

### Miscellaneous
- Sound (decibels)
- Light Intensity (lux)
- Radioactivity (Becquerel, curie)

## Installation

To install, run:

```bash
npm install UniversalConverterJS

## Usage

```
const { convert } = require('UniversalConverterJS');
console.log(convert(1).from('m').to('cm'));  // Output: 100
```

## Directory Structure

```
UniversalConverterJS/
├── src/
│   └── UniversalConverter.js
├── package.json
├── README.md
└── .gitignore
```

## Contribution

Contributions are welcome.

## License

MIT License

Copyright (c) 2023 Danny Castonguay

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

