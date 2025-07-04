This project demonstrates a basic calculator system with two components:

- **ASP.NET Core Web API (Backend)**: Provides endpoints for arithmetic operations (+, -, *, /).
- **HTML/CSS/JavaScript (Frontend)**: A simple web-based UI to interact with the API.

### Technologies Used
- ASP.NET Core Web API
- HTML5
- CSS3
- JavaScript (Fetch API)

### Features
- Perform arithmetic operations via API
- Clean, responsive frontend UI
- Sends requests from JS to API using `fetch`
- Shows results dynamically without page reload

### How It Works
1. User enters two numbers in the HTML form.
2. On button click (+, -, *, /), JavaScript sends a GET request to the API.
3. API processes the request and returns the result.
4. JavaScript displays the result in the browser.

