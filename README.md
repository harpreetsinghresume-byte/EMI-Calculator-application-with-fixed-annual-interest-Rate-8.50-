# Car Loan EMI Calculator

A responsive, user-friendly **Car Loan EMI Calculator** built for Indian currency (₹ INR) with a fixed competitive interest rate of **8.50% p.a.** 

## 🌐 Live Demo

[**Access the Live Calculator Here →**](https://harpreetsinghresume-byte.github.io/EMI-Calculator-application-with-fixed-annual-interest-Rate-8.50-/)

## 🚀 Features

* **Real-time Calculations:** Instantly calculates monthly EMIs, total interest payable, and total payment as you adjust sliders or input values.
* **Indian Currency Formatting:** Displays financial values in standard Indian numbering format (₹ INR).
* **Flexible Inputs:** Adjust car value, down payment, and loan tenure seamlessly.
* **Modern UI:** Clean, responsive design styled with **Tailwind CSS**.
* **Visual Charts:** Interactive doughnut chart showing principal vs. interest breakdown using Chart.js.
* **Print-Friendly Summary:** Generate and print a detailed loan summary report.

## ��️ Tech Stack

* **HTML5** - Structure and layout
* **Tailwind CSS** - Styling and responsive design
* **JavaScript (ES6)** - Interactive calculation logic and real-time DOM updates
* **Chart.js** - Visual data representation
* **FontAwesome Icons** - Beautiful iconography

## 💻 Installation & Usage

1. Clone the repository or download the ZIP file:
   ```bash
   git clone https://github.com/harpreetsinghresume-byte/EMI-Calculator-application-with-fixed-annual-interest-Rate-8.50-.git
   cd EMI-Calculator-application-with-fixed-annual-interest-Rate-8.50-
   ```

2. Open `car_loan_emi_calculator.html` directly in your browser or deploy to a web server.

## 📊 How to Use

1. **Enter Car Value:** Use the input field or slider to set the total car price (₹).
2. **Set Down Payment:** Specify the down payment amount (percentage is auto-calculated).
3. **Choose Loan Tenure:** Select the repayment period in years (1-7 years).
4. **View Results:** See the calculated:
   - Monthly EMI (Equated Monthly Installment)
   - Principal Amount
   - Total Interest Payable
   - Total Payment (Principal + Interest)
   - Visual breakdown chart

5. **Reset:** Click the Reset button to return to default values.
6. **Print Summary:** Click the Summary button to generate and print a detailed loan report.

## 💰 Interest Rate

The calculator uses a **fixed annual interest rate of 8.50% p.a.** as standard for competitive car loans in India.

## 📱 Responsive Design

The calculator is fully responsive and works seamlessly on:
- Desktop (1920px+)
- Tablets (768px - 1024px)
- Mobile devices (320px - 767px)

## 🎨 Customization

To modify the interest rate, edit the following line in the JavaScript section:
```javascript
const result = calculateEMI(loanAmount, 8.50, years);
```

Replace `8.50` with your desired interest rate.

## 📄 License

This project is open-source and available for personal and commercial use.

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for any improvements or bug fixes.

## 👨‍💻 Author

**Harpreet Singh**  
[GitHub](https://github.com/harpreetsinghresume-byte) | [Portfolio](#)

---

**Built with ❤️ using HTML, Tailwind CSS, and JavaScript**
