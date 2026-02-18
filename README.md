# 72(t) SEPP Adventure Engine

A comprehensive financial forecasting tool designed for US retirees planning an international journey. This engine calculates **Substantially Equal Periodic Payments (SEPP)** under the IRS 72(t) rule, allowing for penalty-free early withdrawals from retirement accounts.

## 🚀 Live Demo
Check out the live tool here: [0xvali.github.io/72t](https://0xvali.github.io/72t/)

## 🛠 Features
* **Triple-Method Calculation:** Supports all three IRS-approved methods:
    1.  **Fixed Amortization:** Predictable, high-payout fixed payments.
    2.  **Fixed Annuitization:** Stable annual income based on IRS mortality tables.
    3.  **RMD Method:** Recalculated yearly for maximum portfolio longevity.
* **Global Tax Forecasting:** Built-in logic for destination countries (India, Singapore, Dubai, UK) including residency status tracking (e.g., RNOR/ROR in India).
* **State-Specific Logic:** Auto-populates 2024-2025 tax rates for all 50 US states.
* **Lump Sum Comparison:** Real-time comparison between SEPP withdrawals and immediate cash-out (including 10% penalty and treaty-based tax hits).
* **Dynamic Assumptions:** Adjust growth rates, exchange rates, and currency devaluation to see long-term impacts on your net monthly income.



## 📊 How It Works
The engine runs a year-by-year simulation until age 59.5, calculating:
1.  **Investment Growth:** Based on your custom growth % assumption.
2.  **Tax Burdens:** Combined Federal and State tax rates, adjusting for residency status changes over time.
3.  **Currency Impact:** Converts net annual income to monthly local currency using base exchange rates and forecasted devaluation.

## 🛡️ Requirements
* A modern web browser (Chrome, Firefox, Safari, Edge).
* No installation required; it is a pure HTML/CSS/JS client-side application.

## 📜 Reference
This tool is for educational purposes only. For official rules, please refer to:
[Internal Revenue Service (IRS) - SEPP Guidance](https://www.irs.gov/retirement-plans/substantially-equal-periodic-payments)

## 🤝 Contributing
Feel free to fork this project, report bugs, or suggest new tax residency logic for additional countries via Issues or Pull Requests.