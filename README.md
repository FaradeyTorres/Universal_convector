## Universal Converter Description

### General Structure

**UniversalConverter** is a multifunctional application for converting various measurement units. The program is implemented in Python using the **Tkinter** library for the graphical interface.

### Main Components

1. **Graphical Interface**:
* Fixed-size main window (1000x750)
* Customizable element styles
* Multi-functional frames
* Tab and dropdown menu system

2. **Functional Modules**:
* Physical unit conversion
* Currency conversion (with API support)
* Operation history
* Settings saving

### Supported Conversion Categories

The program supports conversion in the following categories:
* Mass
* Length
* Volume
* Temperature
* Area
* Speed
* Data
* Energy
* Pressure
* Time
* Radiation
* Astronomy
* Cooking
* Angles

### Currency System

The **currency module** works via the exchangerate-api.com API and supports:
* USD
* EUR
* RUB
* GBP
* JPY
* CNY
* AUD
* CAD
* CHF
* INR
* BRL

### Core Features

1. **User Interface**:
* Category selection
* Source and target unit selection
* Numerical input
* Results display
* Last 20 operations history

2. **Additional Features**:
* Conversion mode switching
* History saving to file
* History clearing
* Unit exchange
* Automatic result formatting

### API Usage

For currency conversion, an API key is required. The process:
1. Go to https://www.exchangerate-api.com/
2. Click "Get Free Key"
3. Register via email
4. Receive API key
5. Insert key into the program
6. Save the key

### Saving Settings

The program automatically saves:
* API key in **converter_api.json**
* Currency rates in **currency_rates.json**
* Conversion history in **converter_history.json**

### Usage Recommendations

* Use up-to-date currency rates for maximum accuracy
* Save conversion history for later analysis
* Monitor remaining API requests when using currencies
* Use unit exchange for quick conversion inversion

### History Management

* **History Saving**: last 20 operations can be saved to a text file
* **History Clearing**: clear all records using the "Clear History" button
* **File Format**: files are saved in .txt format with operation numbering

### Interface Recommendations

* **Fullscreen Mode**: recommended to enable for optimal display
* **Screen Resolution**: some buttons may not fit on smaller screens
* **Scaling**: optimal usage with 1000x750 resolution or higher
