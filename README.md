# Currency Converter

## Overview
This is a **Streamlit-based Currency Converter** that allows users to convert amounts between different currencies using real-time exchange rates. It also provides historical exchange rate trends with graphical representation.

App hosted on https://currencyconverter15.streamlit.app

## Features
- Convert currency values between multiple global currencies.
- Fetch real-time exchange rates using **freecurrencyapi**.
- Visualize historical exchange rates with **Matplotlib**.
- Intuitive and interactive UI built with **Streamlit**.
- Swap currencies with a single button click.

## Technologies Used
- **Python**
- **Streamlit** (for UI)
- **Freecurrencyapi** (for exchange rates)
- **Matplotlib** (for plotting graphs)

## Installation
### Prerequisites
Make sure you have Python installed. You can download it from [python.org](https://www.python.org/downloads/).

### Steps
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/currency-converter.git
   ```
2. Navigate to the project directory:
   ```sh
   cd currency-converter
   ```
3. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```

## Usage
1. Select the input currency and enter the amount.
2. Choose the output currency.
3. Click the "Convert" button to see the converted amount.
4. Click the "Graph" button to view historical exchange rate trends.
5. Use the swap button to quickly switch input and output currencies.

## API Key Setup
This project uses **freecurrencyapi** to fetch exchange rates. To use it, get an API key from [freecurrencyapi.com](https://freecurrencyapi.com/) and replace the placeholder in the code:
```python
client = freecurrencyapi.Client('your_api_key_here')
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.


