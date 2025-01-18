# Unit Converter Web Application

## Overview

The **Unit Converter Web Application** is a lightweight and user-friendly tool for converting commonly used units like Celsius to Fahrenheit, Kilograms to Pounds, and Kilometers to Miles. Built with HTML, CSS, and JavaScript, this web application offers an intuitive interface with instant conversion capabilities, providing a seamless user experience.

---

## Prerequisites

To run the **Unit Converter Web Application**, you need:

- **Web Browser**: Any modern browser (Google Chrome, Mozilla Firefox, Safari, Microsoft Edge, etc.).
- **Local Server**: To test locally, you can use Python’s built-in HTTP server or any other static file server.

---

## Installation

### 1. Clone the Repository
Clone the repository to your local machine using Git:

```bash
git clone https://github.com/Aman-Sunesh/Unit-Converter-WebApp.git
cd Unit-Converter-WebApp
```

### 2. Run a Local Server
You can use Python to serve the application locally:

#### Using Python 3:
```bash
python3 -m http.server 8080
```

#### Using Python 2:
```bash
python -m SimpleHTTPServer 8080
```

Navigate to http://0.0.0.0:8080 or http://localhost:8080 in your browser to access the application.

## Usage

### Available Conversions

#### Celsius to Fahrenheit
1. Input the temperature in Celsius.
2. Click the "Convert" button to see the result in Fahrenheit.
3. **Formula:** Celsius = (Fahrenheit - 32) * (5/9)

#### Kilograms to Pounds
1. Input the weight in Kilograms.
2. Click the "Convert" button to see the result in Pounds.
3. **Formula:** Pounds = Kilograms * 2.205

#### Kilometers to Miles
1. Input the distance in Kilometers.
2. Click the "Convert" button to see the result in Miles.
3. **Formula:** Miles = Kilometers / 1.609
---

### Features and Functionalities

#### Interactive User Interface
- Responsive design with easy-to-read input fields and buttons.
- Each conversion section includes input validation and clear instructions.

#### Instant Conversion
- Real-time conversion with JavaScript functions executed on button clicks.

#### Input Validation
- Alerts users to enter valid numeric values.
- Ensures fields are not empty before performing calculations.

#### Clear Instructions
- Each conversion section provides the mathematical formula used for manual verification.

---

### Detailed Features

#### 1. Celsius to Fahrenheit Conversion
- **Input:** Celsius temperature.
- **Output:** Fahrenheit temperature.
- **Validation:**
  - Ensures numeric input.
  - Prompts user if the input field is empty or invalid.

#### 2. Kilograms to Pounds Conversion
- **Input:** Weight in kilograms.
- **Output:** Weight in pounds.
- **Validation:**
  - Ensures numeric input.
  - Prompts user if the input field is empty or invalid.

#### 3. Kilometers to Miles Conversion
- **Input:** Distance in kilometers.
- **Output:** Distance in miles.
- **Validation:**
  - Ensures numeric input.
  - Prompts user if the input field is empty or invalid.

---

### Troubleshooting

#### 1. Local Server Issues
- If the application doesn't load:
  - Ensure you are running a local server in the correct directory.
  - Verify that the server is running on `http://localhost:8080`.

#### 2. Input Validation Errors
- If the conversion doesn't work, ensure you’ve entered a valid numeric value in the input field.

#### 3. Browser Compatibility
- If the layout appears broken, use a modern browser like Chrome or Firefox.

---

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements or additional features. Whether it's enhancing the algorithm, optimizing performance, or adding new functionalities, your contributions are valuable.

---

## Acknowledgments
- **HTML and CSS Documentation:** [W3Schools](https://www.w3schools.com/)
- **JavaScript Documentation:** [MDN Web Docs](https://developer.mozilla.org/)
- **Open Source Community:** For tools and resources.
