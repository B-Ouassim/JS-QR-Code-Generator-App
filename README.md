# 📷 Dynamic QR Code Generator

A utility web application that allows users to instantly convert text or a URL into a scannable QR code image. This project focuses on connecting core front-end logic with external services.

## ✨ Key Features
* **API Integration:** Dynamically fetches the QR code image from a public API based on user input.
* **Input Validation:** Provides visual feedback if the user tries to generate a code from an empty field.
* **Real-time Generation:** Generates and displays the QR code image immediately upon button click.
* **Modern UI:** Clean, centered design using HTML and CSS for an appealing user experience.

## 💻 Technologies Used
* **HTML5:** Structure of the generator card and input form.
* **CSS3:** Custom styling for layout, responsiveness, and visual effects.
* **JavaScript (Vanilla):** Handles user input, calls the external QR code API, and manages the dynamic display of the generated image.

## 🚀 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/JS-QR-Code-Generator-App.git](https://github.com/YourUsername/JS-QR-Code-Generator-App.git)
    ```
2.  **Launch:** Open the `index.html` file in your web browser. No server is required.

## 💡 How it Works
1.  Enter any text (e.g., your name) or a full URL (e.g., a link to your portfolio).
2.  Click the **"Generate QR code"** button.
3.  The JavaScript function sends the data to the external API, which returns a PNG image of the QR code.
4.  The application updates the image source to display the newly generated QR code.
