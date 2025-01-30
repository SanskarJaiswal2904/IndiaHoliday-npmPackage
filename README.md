# IndiaHoliday-npmPackage

## 📦 [india-holiday-1.0 Package on NPM](https://www.npmjs.com/package/india-holiday-1.0)

A simple package to get information about Indian holidays. Whether you're planning your vacation or checking today's holiday, this package has you covered!

---

## 🎥 Inspiration
This package was built with the help of **Web Dev Simplified**. Check out the tutorial I followed:  
[Web Dev Simplified - YouTube](https://www.youtube.com/watch?v=J4b_T-qH3BY&t=249s)

---

## 🚀 Installation

To install the package, simply run the following command:

```bash
npm install india-holiday-1.0
```

---

## 🛠️ Usage

Once installed, you can use this package in your Node.js project to check for holidays. Here’s a quick example:

```javascript
const getHolidayMessage = require('india-holiday-1.0'); // Replace with your package name

// Test with a holiday date
console.log(getHolidayMessage('2024-01-26', true)); // Should return "Happy Republic Day,"

// Test with a non-holiday date
console.log(getHolidayMessage(new Date(), true)); // Should return "Welcome,"
console.log(getHolidayMessage('false' , true)); // Should return Error,
```

---

## 💻 Features

- Get today's holiday in India.
- Check if today is a holiday.
- Easy to use and integrate with your Node.js projects.
- Get color Gradient of India Flag.

---

##  Made with ❤️ by [Sanskar](https://sanskarjaiswal2904.github.io/Sanskar-Website/index.html)

