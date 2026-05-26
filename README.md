<div align="center">

# 💰 Loan Calculator

### *Know your EMI before you borrow.*

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap_4-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

**[🌐 Live Demo →](https://manan-2007.github.io/Loan-Calculator/)**

</div>

---

## 📖 About

**Loan Calculator** is a browser-based EMI tool — the first project built with a genuine real-world use case. You input a loan amount (in ₹), an interest rate (%), and the repayment period in years. After a 2-second simulated loading animation, it displays your monthly payment, total repayment amount, and total interest paid.

Built with Bootstrap 4 for layout and a dark UI theme, it demonstrates form handling, input validation, and mathematical computation in Vanilla JavaScript.

---

## ✨ Features

- **EMI Calculation** — Uses the standard reducing-balance formula
- **Three Outputs** — Monthly payment, total payment, total interest
- **Loading Animation** — 2-second spinner before showing results (simulated async)
- **Input Validation** — Shows a dismissable error alert for invalid/empty inputs
- **Dark UI** — Bootstrap 4 dark card on a dark body background
- **₹ Symbol** — Indian Rupee input grouping for localised context

---

## 📐 Formula Used

```
EMI = P × r × (1 + r)ⁿ / [(1 + r)ⁿ − 1]

where:
  P = Principal loan amount
  r = Monthly interest rate (annual rate ÷ 12 ÷ 100)
  n = Total number of monthly payments (years × 12)
```

> **Example:** ₹5,00,000 at 10% p.a. for 5 years → EMI ≈ ₹10,624 / month

---

## 🛠️ Tech Stack

| Layer | Detail |
|---|---|
| Structure | HTML5 |
| Styling | Bootstrap 4.0 + inline CSS overrides |
| Logic | Vanilla JavaScript |
| Hosting | GitHub Pages |

---

## 📂 Project Structure

```
Loan-Calculator/
├── index.html      # Main UI — form, loader, results
└── app.js          # All JS logic — calculation, validation, error handling
```

---

## 🚀 Getting Started

No build step needed.

```bash
git clone https://github.com/Manan-2007/Loan-Calculator.git
cd Loan-Calculator
# Open index.html in any browser
```

---

## 🎓 Context

> This was the **first project built with a real use case** — not just a sample page. It reinforced form handling, DOM manipulation, and practical math in JavaScript. A meaningful step up from purely static websites.

---

<div align="center">

Made by **Manan** · [GitHub](https://github.com/Manan-2007)

</div>
