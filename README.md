# MyInterest

MyInterest is a simple web application for managing a personal credit line and tracking the interest generated each quarter. The entire state is stored locally in your browser via **LocalStorage**, so no information is sent to any server or third party.

## Features

- Configure your credit limit, annual interest rate and start date.
- Register withdrawals and repayments with their amount and date.
- Automatic calculation of the current balance, available credit and accrued interest for the quarter.
- Dashboard with recent activity and a history table where you can delete entries.
- Interest forecast for the current and next quarter, including a countdown to the next payment date.
- Persistent storage using LocalStorage so your data is preserved between sessions.

## Usage

### Online

You can try the application directly from GitHub Pages: <https://p2pinv88.github.io/MyInterest/>.
All calculations run in the browser and your data stays only on your device.

### Local

1. Clone this repository or download the `index.html` file.
2. Open `index.html` in your browser or serve it with a small local server:
   ```bash
   python3 -m http.server
   ```
   Then visit [http://localhost:8000](http://localhost:8000) in your browser.
3. Go to the **Settings** section and set up your credit line parameters.
4. Record withdrawals or repayments in **Transactions**.
5. Check the **Home** panel for a summary and interest forecast.

## Contributing

Contributions are welcome! Please use the provided issue and pull request templates when opening new tickets or submitting changes.
