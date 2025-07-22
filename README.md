# Password Strength Checker

A simple, client-side web application designed to help users create strong and secure passwords by evaluating them against customizable criteria. This tool prioritizes privacy, as no password data is ever stored or transmitted.

## ✨ Features

* **Real-time Strength Feedback:** Get instant feedback on your password's strength as you type.

* **Customizable Rules:** Define your own password criteria, including:

    * Minimum overall length.

    * Minimum number of uppercase letters.

    * Minimum number of lowercase letters.

    * Minimum number of digits.

    * Minimum number of special characters.

* **Privacy-Focused:** All password checking logic runs directly in your browser. Your password is **never** sent to a server or stored anywhere.

* **Password Visibility Toggle:** Easily show or hide your entered password with an eye icon.

* **Dynamic Strength Bar:** A visual indicator that updates in real-time to reflect your password's compliance with the set rules.

* **Informative Feedback:** Clear messages indicate which rules your password meets or fails.

* **Light/Dark Theme:** Switch between light and dark modes for comfortable viewing.

* **Responsive Design:** Optimized for various screen sizes, from mobile to desktop.

## 🚀 Technologies Used

* **HTML5:** For the basic structure of the web page.

* **CSS3:** For styling and layout, maintaining a clean and modern aesthetic.

* **JavaScript (jQuery):** For interactive elements, real-time password analysis, and dynamic UI updates.

## 📦 Installation and Setup

This is a client-side application, so setting it up is straightforward.

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/Password-Strength-Checker.git](https://github.com/YOUR_USERNAME/Password-Strength-Checker.git)
    cd Password-Strength-Checker
    ```
    (Replace `YOUR_USERNAME` with your actual GitHub username).

2.  **Download jQuery:**
    Download the minified jQuery 3.x version from its official CDN:
    `https://code.jquery.com/jquery-3.7.0.min.js`
    Save this file as `jquery-3.7.0.min.js` directly into your `Password-Strength-Checker` project folder (the same folder as `index.html` and `style.css`).

3.  **Run Locally:**
    You can open `index.html` directly in your web browser, but for best performance and to avoid browser security restrictions, it's recommended to use a local web server.

    * **Using VS Code Live Server Extension (Recommended):**
        If you use VS Code, install the "Live Server" extension. Right-click on `index.html` in the explorer and select "Open with Live Server."

    * **Using Python's Simple HTTP Server:**
        Navigate to your project directory in your terminal and run:
        ```bash
        python -m http.server 8000
        ```
        Then, open your web browser and go to `http://localhost:8000/`.

## 💡 Usage

1.  **Enter Your Password:** Type your desired password into the "Enter your password" input field. The strength analysis will update in real-time.

2.  **Toggle Visibility:** Click the eye icon next to the password input to show or hide the characters.

3.  **Check Password:** Click the "Check Password" button to manually trigger the strength analysis.

4.  **Strength Bar:** Observe the colored bar and label below the input field, which visually represent the password's strength based on the rules.

5.  **View Results:** Below the strength bar, you'll see a detailed list of checks, indicating whether your password meets each requirement with a ✔️ or ❌.

6.  **Theme Toggle:** Use the "Light" / "Dark" toggle in the top-right corner to switch between themes.

7.  **About This Tool:** Click the "ⓘ Info" button in the top-right for information about the application's privacy and functionality.

8.  **Advanced Options:**

    * Click the "⚙️ Advanced Options" button to open a modal where you can customize the password strength rules.

    * Adjust the "Minimum Length" and the minimum counts for "Uppercase Letters," "Lowercase Letters," "Numbers," and "Special Characters."

    * Set a value of `0` for any character type if you do not wish to enforce that specific requirement.

    * Click "Apply" for minimum length or "Apply Character Rules" to save your custom settings.

    * Click the "ⓘ Info" button next to "Advanced Options" for an explanation of these customizable rules.

## 🤝 Contributing

Feel free to fork this repository, open issues, or submit pull requests if you have suggestions for improvements or new features!

## 📄 License

This project is open source and available under the [MIT License](https://www.google.com/search?q=LICENSE).