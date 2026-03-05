# 🔢 Advanced Calculator React App

A professional-grade, modern, scientific calculator built with **React.js**. This app supports advanced mathematical operations, unit conversions, voice input, history tracking, theme toggling, and scientific notation formatting. Designed for clarity, functionality, and production-readiness.

--- 

## ✨ Features

### 🧮 Core Calculator Functions
- Addition, Subtraction, Multiplication, Division 
- Decimal handling and parentheses   
- Square root support via `√`      
- Trigonometric functions: `sin`, `cos`, `tan`  
- Logarithmic function: `log`     
- Scientific notation toggle (`sci`) 
- Error handling for invalid inputs   
 
### 🎨 Theming
- Toggle between **Light** and **Dark** modes  
- Button: 🌙 / ☀️

### 🧠 History Tracking 
- All calculations are stored in a session-based history
- History is displayed in a **left-hand sidebar**
- Most recent calculations appear at the top

### 🔁 Unit Conversion (Manual)
- Choose unit via `unit` button
- Apply conversion with the `convert` button
- Supported conversions:
  - `m → cm` (× 100)
  - `kg → g` (× 1000)
  - `cm → m` (× 0.01)
  - `g → kg` (× 0.001)

### 🎙️ Voice Input
- Dictate mathematical expressions via microphone
- Uses Web Speech API (`SpeechRecognition`)
- Accurate recognition in modern browsers

### 📋 Clipboard Integration
- Copy current expression/output using `copy` button

---

## 📁 Project Structure

```
Directory structure:
└── baladurgag24-django-event-countdown-website/
    ├── README.md
    ├── db.sqlite3
    ├── LICENSE
    ├── manage.py
    ├── countdown/
    │   ├── __init__.py
    │   ├── asgi.py
    │   ├── settings.py
    │   ├── urls.py
    │   ├── wsgi.py
    │   └── __pycache__/
    └── home/
        ├── __init__.py
        ├── admin.py
        ├── apps.py
        ├── models.py
        ├── tests.py
        ├── urls.py
        ├── views.py
        ├── __pycache__/
        ├── migrations/
        │   ├── 0001_initial.py
        │   ├── __init__.py
        │   └── __pycache__/
        └── templates/
            └── myapp.html

```

## 🚀 Getting Started

Follow these instructions to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/BALADURGAG24/react-advanced-calculator.git
cd react-advanced-calculator
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run the Development Server

```bash
npm start
```

This will open the app in your default browser at `http://localhost:3000`.

---

## 📦 Production Build

To build the project for production use:

```bash
npm run build
```

---


## 🧪 Technical Notes

- **Trigonometric and logarithmic** functions use `Math` API in radians.
- **Speech-to-text** accuracy may vary based on microphone input and browser.
- **Scientific notation** outputs values like `1.23e+4` for compact viewing.
- Use parentheses to control order of operations, e.g., `sin(30 + 45)`.

---

## 🧰 Technologies Used

- **React 18+**
- **Framer Motion** – animation transitions
- **Web Speech API** – voice input
- **Clipboard API** – copy-to-clipboard
- **Vanilla CSS** – responsive UI and dark mode

---

## 🛠️ Future Improvements

- Degree/Radian toggle for trig functions
- LocalStorage sync for history
- Enhanced parser (using math.js)
- Unit selection dropdown instead of toggle cycle

---

## 📝 License

Licensed under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

Developed by [BALADURGAG24].  
Feel free to open issues, PRs, or feature requests.

---























