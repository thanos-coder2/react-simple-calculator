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

Greek Version (Ελληνικά)
![Calculator Screenshot](assets/calculator-screen1.png)
![Calculator Screenshot2](assets/calculator-screen2.png)
Περιγραφή

Ένας απλός υπολογιστής αριθμητικών πράξεων κατασκευασμένος με React χρησιμοποιώντας functional components και React Hooks.

Η εφαρμογή επιτρέπει στον χρήστη να πραγματοποιεί βασικές μαθηματικές πράξεις μέσα από ένα καθαρό και εύχρηστο interface.

Λειτουργίες
Βασικές πράξεις (+ − × ÷)
Καθαρισμός εισόδου
Responsive layout με CSS Grid
Χρήση React Hooks (useState)
Διαχείριση σφαλμάτων σε λάθος εκφράσεις
Τεχνολογίες
React
JavaScript (ES6)
HTML
CSS
React Hooks
Πώς λειτουργεί

Η εφαρμογή αποθηκεύει την έκφραση που πληκτρολογεί ο χρήστης σε ένα state variable.

const [input, setInput] = useState("");

Όταν πατηθεί ένα κουμπί, η τιμή προστίθεται στο input.

Όταν πατηθεί το =, γίνεται υπολογισμός της έκφρασης και εμφανίζεται το αποτέλεσμα.

Αν η έκφραση δεν είναι έγκυρη, εμφανίζεται μήνυμα Error.

Εγκατάσταση
Κατέβασε το repository
git clone https://github.com/thanos-coder2/react-simple-calculator.git
Μπες στον φάκελο
cd react-calculator
Εγκατέστησε τα dependencies
npm install
Εκκίνηση εφαρμογής
npm start

Η εφαρμογή θα ανοίξει στο:

http://localhost:3000
Μελλοντικές Βελτιώσεις
Αντικατάσταση του eval() με ασφαλέστερο parser
Υποστήριξη πληκτρολογίου
Scientific calculator λειτουργίες
Καλύτερο mobile UI
Animations στο interface




