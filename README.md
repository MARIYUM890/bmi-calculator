# ⚖️ BMI Calculator

A simple and responsive Body Mass Index (BMI) Calculator built using HTML, CSS, and JavaScript. This project allows users to calculate their BMI based on height and weight inputs and provides health category feedback.

---

## 🚀 Live Demo

> Coming Soon (Deploy via GitHub Pages)

---

## 📖 About the Project

The **BMI Calculator** is a beginner-friendly project that demonstrates how to handle user input, perform calculations, and dynamically update the UI.

It helps in:

* Understanding DOM manipulation
* Working with form inputs
* Applying real-world formulas in JavaScript
* Building interactive UI components

---

## 🛠️ Tech Stack

* **HTML5** – Structure and input fields
* **CSS3** – Styling and responsive layout
* **JavaScript (Vanilla JS)** – Calculation logic

---

## ⚙️ BMI Formula

BMI = \frac{weight,(kg)}{(height,(m))^2}

---

## ✨ Features

* User input for height (cm) and weight (kg)
* Instant BMI calculation
* Displays BMI value
* Shows health category:

  * Underweight
  * Normal weight
  * Overweight
  * Obese
* Responsive design (mobile-friendly)
* Input validation handling

---

## 📂 Project Structure

```id="bmi001"
bmi-calculator/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## 🧠 How It Works

1. User enters height (in cm) and weight (in kg)
2. Height is converted from cm to meters
3. BMI is calculated using the formula
4. Result is displayed with category classification

---

## 🧮 Example Logic

```javascript id="bmiLogic"
function calculateBMI() {
  const height = document.getElementById("height").value / 100;
  const weight = document.getElementById("weight").value;

  const bmi = (weight / (height * height)).toFixed(2);

  // Display BMI
}
```

---

## 📊 BMI Categories

| BMI Range      | Category      |
| -------------- | ------------- |
| Less than 18.5 | Underweight   |
| 18.5 – 24.9    | Normal weight |
| 25 – 29.9      | Overweight    |
| 30 and above   | Obese         |

---

## 📦 Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/bmi-calculator.git
   ```

2. Navigate to the project:

   ```bash
   cd bmi-calculator
   ```

3. Run locally:

   * Open `index.html` in your browser

---

## 🔧 Customization

You can enhance the project by:

* Adding unit toggle (kg/lbs, cm/feet)
* Integrating health tips based on BMI
* Adding charts/visual indicators
* Connecting with a backend for user data tracking

---

## 📈 Future Enhancements

* Add user profile tracking
* Store BMI history (localStorage or database)
* UI improvements with animations
* Convert into reusable JS component

---

## 🎯 Use Cases

* Health and fitness websites
* Personal dashboards
* Educational projects
* Portfolio showcase

---

## 🤝 Contribution

This is a personal learning project. Suggestions are welcome.

---

## 📧 Contact

* GitHub: MARIYUM890

---

## 🏁 Conclusion

This BMI Calculator project is a strong example of applying logic, user interaction, and real-world problem solving in frontend development.

---

⭐ Star this repository if you found it useful!
