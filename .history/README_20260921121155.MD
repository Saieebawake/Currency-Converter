# 💱 Currency Converter

A simple and interactive **Currency Converter Web Application** built using **HTML, CSS, and JavaScript**.  
The application uses the **Frankfurter API** to fetch real-time exchange rates and convert currencies dynamically.

## 🚀 Live Demo

Add your deployed project link here:

**Live Demo:** [Add your GitHub Pages / Vercel link here]

## 📌 Features

- 💰 Enter the amount you want to convert
- 🌍 Select currencies from a large list of currencies
- 🔄 Convert between different currencies
- 🏳️ Displays the corresponding country flag
- 📡 Fetches exchange rates using an API
- ⚡ Updates the conversion result dynamically
- 📱 Simple and clean user interface

## 🛠️ Technologies Used

- **HTML5** – Structure of the webpage
- **CSS3** – Styling and layout
- **JavaScript** – Functionality and API integration
- **Frankfurter API** – Exchange rate data
- **FlagsAPI** – Country flag images
- **Font Awesome** – Icons

## 🔗 APIs Used

### Frankfurter API

Used to fetch the latest available currency exchange rates.

Example:
https://api.frankfurter.dev/v2/rate/usd/inr


### FlagsAPI

Used to display country flags based on currency selection.

Example:
https://flagsapi.com/US/flat/64.png

## 📂 Project Structure
Currency-Converter/
│
├── index.html
├── currconverter.css
├── currconverter.js
├── countrycodes.js
└── README.md

## ⚙️ How It Works

1. The user enters an amount.
2. The user selects the **From** currency.
3. The user selects the **To** currency.
4. JavaScript creates the API URL using the selected currencies.
5. The `fetch()` method sends a request to the Frankfurter API.
6. The API returns the exchange rate in JSON format.
7. JavaScript extracts the `rate` value from the response.
8. The entered amount is multiplied by the exchange rate.
9. The converted amount is displayed on the webpage.

### Example

```text
100 USD → INR

Exchange Rate = 88.50

100 × 88.50 = 8850 INR

## 🧠 What I Learned

While building this project, I learned:

- How to work with **JavaScript APIs**
- How to use `fetch()`
- How to work with **Promises and async/await**
- How to convert an API response into JSON using `response.json()`
- How to access data from a JSON object
- How to dynamically create `<option>` elements
- How to use JavaScript to update HTML elements
- How to dynamically change images using JavaScript
- How to construct API URLs using template literals
- How to perform calculations using API data

## 🔮 Future Improvements

- Add a currency swap button
- Add automatic conversion when the currency changes
- Add better error handling when the API is unavailable
- Add loading animation while fetching data
- Improve mobile responsiveness
- Add conversion history
- Improve the overall UI/UX

## 👩‍💻 Author

**Sai Bawake**

Computer Science Engineering Student

### ⭐ If you like this project, consider giving it a star!