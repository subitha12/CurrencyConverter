# CurrencyConverter

CurrencyConverter is a simple web application that allows users to convert amounts between different currencies. It fetches current exchange rates from the ExchangeRate-API and performs the conversion.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [API Reference](#api-reference)
- [Contributing](#contributing)
- [License](#license)

## Installation

Instructions on how to set up the project locally:

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/currencyconverter.git
    ```
2. Navigate to the project directory:
    ```sh
    cd currencyconverter
    ```
3. Open `index.html` in your browser to view the project.

## Usage

1. Open the application in your web browser.
2. Select the currencies you want to convert from and to.
3. Enter the amount to be converted.
4. Click the "Convert" button to retrieve and display the converted amount.

## Features

- Real-time currency conversion.
- Supports multiple currencies.
- User-friendly interface with responsive design.

## Technologies Used

### HTML
Used to structure the content of the web pages. Key files include:
- `index.html` - The main entry point of the application.

### CSS
Used to style the content of the web pages. Key files include:
- `styles.css` - Contains all the styles for the project.

### JavaScript
Used to add interactivity and handle logic in the web application. Key files include:
- `script.js` - Contains the main JavaScript code for the project.

### API
CurrencyConverter interacts with the ExchangeRate-API to fetch current exchange rates.

## API Reference

### ExchangeRate-API
- **Endpoint:** `https://v6.exchangerate-api.com/v6/YOUR-API-KEY/latest/USD`
- **Method:** GET
- **Parameters:**
    - `base` (optional): Base currency (default is USD).
    - `symbols` (optional): Comma-separated list of target currencies.
- **Example Request:**
    ```sh
    https://v6.exchangerate-api.com/v6/YOUR-API-KEY/latest/USD
    ```
- **Example Response:**
    ```json
    {
        "base_code": "USD",
        "conversion_rates": {
            "EUR": 0.85,
            "GBP": 0.75,
            "JPY": 110.00
        }
    }
    ```

## Contributing

Instructions for contributing to the project:

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature/YourFeature
    ```
3. Make your changes and commit them:
    ```sh
    git commit -m 'Add your feature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature/YourFeature
    ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
