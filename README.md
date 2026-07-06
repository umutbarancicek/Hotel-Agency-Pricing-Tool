# 🏨 Hotel Agency Pricing Tool

[![Language](https://img.shields.io/github/languages/top/umutbarancicek/Hotel-Agency-Pricing-Tool?color=orange)](https://github.com/umutbarancicek/Hotel-Agency-Pricing-Tool)
[![License](https://img.shields.io/github/license/umutbarancicek/Hotel-Agency-Pricing-Tool)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/umutbarancicek/Hotel-Agency-Pricing-Tool)](https://github.com/umutbarancicek/Hotel-Agency-Pricing-Tool/commits/main)
[![Repo Size](https://img.shields.io/github/repo-size/umutbarancicek/Hotel-Agency-Pricing-Tool)](https://github.com/umutbarancicek/Hotel-Agency-Pricing-Tool)

An intuitive, client-side web application designed for travel agencies and hotel managers to calculate complex pricing structures instantly. This tool simplifies the process of determining total stay costs by factoring in seasonal rates, agency commissions, and guest demographics.

---

## 📖 About the Project

In the hospitality industry, pricing is rarely static. Between high/low seasons, agency markups, and varying room types, calculating a final quote for a client can be error-prone and time-consuming. 

The **Hotel Agency Pricing Tool** provides a streamlined interface where users can input stay parameters and receive a detailed breakdown of costs. Built with a "Mobile First" philosophy, it allows agents to provide quotes on the go, whether they are in the office or on a call.

## ✨ Features

-   **Dynamic Rate Calculation:** Calculate costs based on check-in/check-out dates.
-   **Seasonal Adjustments:** Support for different price points for High, Mid, and Low seasons.
-   **Agency Commission Management:** Easily toggle or adjust percentage-based markups.
-   **Responsive Design:** Fully functional on desktops, tablets, and smartphones.
-   **Client-Side Processing:** Fast calculations with no server-side overhead or database delays.
-   **Detailed Breakdown:** View base price, taxes, and service fees separately.

## 🛠 Tech Stack

-   **HTML5:** Semantic structure for high accessibility and SEO.
-   **CSS3:** Modern layouts using Flexbox and Grid, including Custom Properties (CSS Variables) for easy theming.
-   **JavaScript (ES6+):** Vanilla logic for high-performance calculations and DOM manipulation without the weight of heavy frameworks.

## 🚀 Installation

Since this is a frontend-focused project, no complex environment setup is required.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/umutbarancicek/Hotel-Agency-Pricing-Tool.git
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd Hotel-Agency-Pricing-Tool
    ```

3.  **Run the application:**
    Simply open the `index.html` file in your preferred web browser:
    ```bash
    open index.html # On macOS
    # Or just double-click the file in your explorer
    ```

## 💡 Usage

To use the tool effectively:

1.  **Select Dates:** Use the date picker to define the stay duration.
2.  **Input Rates:** Enter the base nightly rate for the selected room category.
3.  **Define Multipliers:** Add any specific agency commission percentages (e.g., `10%`).
4.  **View Results:** The "Total Price" will update in real-time as you modify the input fields.

```javascript
// Example of the underlying logic structure
const calculateTotal = (baseRate, days, commission) => {
    const subtotal = baseRate * days;
    return subtotal + (subtotal * (commission / 100));
};
```

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Developed by [Umut Baran Çiçek](https://github.com/umutbarancicek)*
