React Simple Calculator 
![Calculator Screenshot](assets/calculator-screen1.png)
![Calculator Screenshot2](assets/calculator-screen2.png)
English | [Ελληνικά](README_GR.md)
A simple calculator application built with React using functional components and React Hooks.

The application allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division through a clean and responsive interface.

Features
Basic arithmetic operations (+ − × ÷)
Clear input functionality
Responsive calculator layout using CSS Grid
Built with React functional components
Uses React Hooks (useState) for state management
Error handling for invalid expressions
Technologies Used
React
JavaScript (ES6)
HTML5
CSS3
React Hooks
Project Structure
project1-calculator
│
├── src
│   ├── Calculator.js
│   ├── Calculator.css
│   ├── App.js
│   └── index.js
│
├── public
│
└── package.json
How It Works

The calculator stores the current input inside a state variable.

const [input, setInput] = useState("");

When a button is clicked, the value is appended to the current input.

const handleClick = (value) => {
  setInput((prev) => prev + value);
};

When the equals button is pressed, the expression is evaluated and the result is displayed.

setInput(eval(input).toString());

If the expression is invalid, the calculator shows an error message.

Installation and Setup
Clone the repository
git clone https://github.com/thanos-coder2/react-simple-calculator.git
Navigate into the project folder
cd react-calculator
Install dependencies
npm install
Run the development server
npm start

The application will start at:

http://localhost:3000
Future Improvements

Possible improvements for this project:

Replace eval() with a safer math parser
Add keyboard support
Add scientific calculator functions
Improve mobile responsiveness
Add animations or UI enhancements

# React Simple Calculator

![Calculator Screenshot](assets/calculator-screen1.png)

![Calculator Screenshot2](assets/calculator-screen2.png)

[English](README.md) | Ελληνικά

---

## Περιγραφή Project GR

Πρόκειται για μια απλή εφαρμογή **Αριθμομηχανής**, η οποία αναπτύχθηκε με **React**, χρησιμοποιώντας **Functional Components** και **React Hooks**.

Η εφαρμογή επιτρέπει στον χρήστη να πραγματοποιεί βασικές αριθμητικές πράξεις, όπως πρόσθεση, αφαίρεση, πολλαπλασιασμό και διαίρεση, μέσα από ένα καθαρό και responsive περιβάλλον χρήσης.

---

## Χαρακτηριστικά

* Βασικές αριθμητικές πράξεις (+ − × ÷)
* Λειτουργία καθαρισμού της εισόδου (Clear)
* Responsive διάταξη με χρήση CSS Grid
* Ανάπτυξη με React Functional Components
* Διαχείριση κατάστασης μέσω του React Hook `useState`
* Εμφάνιση μηνύματος σφάλματος σε μη έγκυρες μαθηματικές εκφράσεις

---

## Τεχνολογίες

* React
* JavaScript (ES6)
* HTML5
* CSS3
* React Hooks

---

## Δομή Project

```text
project1-calculator
│
├── src
│   ├── Calculator.js
│   ├── Calculator.css
│   ├── App.js
│   └── index.js
│
├── public
│
└── package.json
```

---

## Τρόπος Λειτουργίας

Η αριθμομηχανή αποθηκεύει την τρέχουσα έκφραση σε μία μεταβλητή κατάστασης (state).

```javascript
const [input, setInput] = useState("");
```

Κάθε φορά που ο χρήστης πατάει ένα κουμπί, η αντίστοιχη τιμή προστίθεται στην ήδη υπάρχουσα έκφραση.

```javascript
const handleClick = (value) => {
  setInput((prev) => prev + value);
};
```

Όταν πατηθεί το κουμπί **=**, η μαθηματική έκφραση υπολογίζεται και εμφανίζεται το αποτέλεσμα.

```javascript
setInput(eval(input).toString());
```

Εάν η έκφραση δεν είναι έγκυρη, εμφανίζεται κατάλληλο μήνυμα σφάλματος αντί να τερματιστεί η εφαρμογή.

---

## Εγκατάσταση και Εκτέλεση

### 1. Κλωνοποίηση του repository

```bash
git clone https://github.com/thanos-coder2/react-simple-calculator.git
```

### 2. Μεταφορά στον φάκελο του project

```bash
cd react-calculator
```

### 3. Εγκατάσταση των απαραίτητων πακέτων

```bash
npm install
```

### 4. Εκκίνηση του development server

```bash
npm start
```

Η εφαρμογή θα είναι διαθέσιμη στη διεύθυνση:

```text
http://localhost:3000
```

---

## Μελλοντικές Βελτιώσεις

Πιθανές επεκτάσεις του project:

* Αντικατάσταση της `eval()` με ασφαλέστερο parser μαθηματικών εκφράσεων
* Υποστήριξη πληκτρολογίου
* Προσθήκη λειτουργιών επιστημονικής αριθμομηχανής
* Περαιτέρω βελτίωση του responsive σχεδιασμού για κινητές συσκευές
* Προσθήκη animations και επιπλέον βελτιώσεων στο περιβάλλον χρήσης (UI)

---

## Τι Έμαθα

Μέσα από το συγκεκριμένο project εξασκήθηκα σε:

* React Components
* React Hooks (`useState`)
* State Management
* Event Handling
* JavaScript ES6
* Responsive Design
* CSS Grid Layout
* Διαχείριση σφαλμάτων (Error Handling)
* Δομή και οργάνωση εφαρμογών React

