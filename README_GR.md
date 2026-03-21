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
git clone https://github.com/yourusername/react-calculator.git
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