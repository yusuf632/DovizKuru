Currency Exchange Application

This project is a real-time currency exchange application that allows users to convert between different currencies using live exchange rates.

Features
💱 Real-time currency conversion

🌐 Support for 35+ different currencies

🔄 Bidirectional conversion

⚡ Instant calculation

📱 Responsive design

💰 Accurate decimal formatting

Technologies

- HTML5 - Structural content

- CSS3 - Flexbox layout and styling

- JavaScript (ES6) - Currency conversion logic

- Free Currency API - Real-time exchange rates

- Font Awesome - Icons

Installation

- Download the project files to your computer

- Open the index.html file in your browser

- Start converting currencies!

Usage

Currency Conversion

- Enter the amount you want to convert in the "Amount" field

- Select the source currency from the first dropdown

- Select the target currency from the second dropdown

- The converted amount will automatically appear in the result field

Supported Currencies

USD, EUR, JPY, BGN, CZK, DKK, GBP, HUF, PLN, RON, SEK, CHF, ISK, NOK, HRK, RUB, TRY, AUD, BRL, CAD, CNY, HKD, IDR, ILS, INR, KRW, MXN, MYR, NZD, PHP, SGD, THB, ZAR

API Integration

Free Currency API

- The application uses Free Currency API for real-time exchange rates

- API endpoint: https://api.freecurrencyapi.com/v1/latest

- Secure access with API key authentication

- Base currency parameter for dynamic conversions

Design Features

Responsive Layout

- Flexbox-based centered layout

- Clean and intuitive user interface

- Proper spacing and alignment

- Antique white background with light grey borders

User Interface Elements

- Number input for amount

- Dropdown selectors for currency selection

- Arrow icon indicating conversion direction

- Read-only result field

- Copyright footer

Developer Notes
JavaScript Architecture

Currency Class (currency.js)

- Handles API communication

- Performs currency conversion calculations

- Returns promises for async operations

Main Application (main.js)

- DOM element selection

- Event listener management

- User input processing

- Result display formatting

Key Functions

- runEventListeners(): Sets up input event listeners

- exchange(): Handles the conversion process

- Real-time updates on input changes

CSS Features

- Centered container layout

- Consistent padding and margins

- Clean typography

- Responsive input and select elements

Important Note

⚠️ Warning: This application contains an API key for Free Currency API. For production use:

- Use environment variables to secure API keys

- Implement rate limiting

- Consider using a backend service to hide API keys

- Monitor API usage to avoid exceeding limits

Default Settings

- Default Source Currency: USD (US Dollar)

- Default Target Currency: TRY (Turkish Lira)

- Result Precision: 3 decimal places

License

- Copyright © Enes Bayram

This project is developed for educational purposes. Please ensure compliance with the Free Currency API terms of service when using this application.
