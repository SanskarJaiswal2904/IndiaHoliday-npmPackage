```markdown
# IndiaHoliday-npmPackage

## 📦 [india-holiday-2.0 Package on NPM](https://www.npmjs.com/package/india-holiday-2.0)

A simple package to get information about Indian holidays. Whether you're planning your vacation or checking today's holiday, this package has you covered!

---

## 🎥 Inspiration
This package was built with the help of **Web Dev Simplified**. Check out the tutorial I followed:  
[Web Dev Simplified - YouTube](https://www.youtube.com/watch?v=J4b_T-qH3BY&t=249s)

---

## 🚀 Installation

To install the package, simply run the following command:

```bash
npm install india-holiday-2.0
```

---

## 🛠️ Usage

Once installed, you can use this package in your Node.js project to check for holidays. Here’s a quick example:

```javascript
// Import the package
const holiday = require('india-holiday-2.0');

// Get today's holiday
console.log(holiday.getTodayHoliday());

// Get holidays for a specific year
console.log(holiday.getHolidays(2025));

// Check if today is a holiday
if (holiday.isHolidayToday()) {
    console.log("Today is a holiday!");
} else {
    console.log("No holiday today.");
}
```

---

## 💻 Features

- Get today's holiday in India.
- Check if today is a holiday.
- Get holidays for a specific year.
- Easy to use and integrate with your Node.js projects.

---

##  Made with ❤️ by [Sanskar](https://sanskarjaiswal2904.github.io/Sanskar-Website/index.html)

