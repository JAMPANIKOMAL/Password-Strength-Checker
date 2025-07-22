# Password Strength Checker

A simple, privacy-focused web app to help users create strong passwords by checking them against customizable criteria. All password analysis happens locally—your data is never sent or stored.

[https://jampanikomal.github.io/Password-Strength-Checker/](https://jampanikomal.github.io/Password-Strength-Checker/)


## ✨ Features

- Enter your password and click "Check Password" for analysis.
- **Animated Rule Display:** Rules are checked and shown one by one with smooth animation; the strength bar updates progressively.
- **Customizable Rules:** Set requirements for:
    - Minimum length
    - Uppercase letters
    - Lowercase letters
    - Digits
    - Special characters
- **Privacy-Focused:** All logic runs in your browser; passwords are never transmitted or stored.
- **Password Visibility Toggle:** Show/hide your password with an eye icon (visible by default).
- **Dynamic Strength Bar:** Visual indicator updates as rules are checked.
- **Informative Feedback:** See which rules your password meets or fails.
- **Light/Dark Theme:** Switch between themes for comfortable viewing.
- **Responsive Design:** Works on mobile and desktop.

## 🚀 Technologies Used

- **HTML5:** Page structure
- **CSS3:** Styling and layout
- **JavaScript (jQuery):** Interactivity, analysis, and UI updates

## 📦 Installation and Setup

1. **Clone the Repository:**
     ```sh
     git clone https://github.com/YOUR_USERNAME/Password-Strength-Checker.git
     cd Password-Strength-Checker
     ```
     *(Replace `YOUR_USERNAME` with your GitHub username)*

2. **Download jQuery:**
     - Get [jquery-3.7.0.min.js](https://code.jquery.com/jquery-3.7.0.min.js) and save it in your project folder.

3. **Run Locally:**
     - Open `index.html` in your browser, or use a local server for best results.

     **Using VS Code Live Server:**
     - Install the "Live Server" extension, right-click `index.html`, and select "Open with Live Server."

     **Using Python HTTP Server:**
     ```sh
     python -m http.server 8000
     ```
     - Visit [http://localhost:8000/](http://localhost:8000/) in your browser.

## 💡 Usage

- **Enter Password:** Type your password in the input field.
- **Toggle Visibility:** Click the eye icon to show/hide your password.
- **Check Password:** Click "Check Password" to analyze strength.
- **Strength Bar:** View the colored bar and label for password strength.
- **View Results:** See which rules are met (✔️) or failed (❌).
- **Theme Toggle:** Switch between light and dark modes.
- **About:** Click "ⓘ Info" for privacy and app details.

**Advanced Options:**
- Click "⚙️ Advanced Options" to customize rules.
- Adjust minimum length and character type requirements.
- Set any value to 0 to disable a rule.
- Click "Apply" to save changes.
- "ⓘ Info" next to Advanced Options explains each rule.

## 🤝 Contributing

Fork, open issues, or submit pull requests for improvements or new features!

## 🤖 AI Assistance

Developed with help from an AI model to enhance features and UI.

## 📄 License

Open source under the MIT License.
