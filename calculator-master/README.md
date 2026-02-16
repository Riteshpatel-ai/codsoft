# 🧮 Web Calculator

A clean and modern web-based calculator built with HTML, CSS, and vanilla JavaScript. This calculator performs basic arithmetic operations including addition, subtraction, multiplication, division, and percentage calculations without relying on the eval() function.

![Calculator Screenshot](preview.png)
*Interactive calculator with colorful operator buttons*

## 🚀 Features

- **Basic Arithmetic Operations**: Addition (+), Subtraction (-), Multiplication (×), Division (÷)
- **Percentage Calculations**: Quick percentage computations
- **Clear Functions**: 
  - C (Clear): Clears all inputs and history
  - CE (Clear Entry): Removes the current entry
- **History Display**: Shows the complete calculation expression
- **Output Display**: Shows current number or result
- **Input Validation**: Prevents invalid mathematical expressions
- **Colorful UI**: Each operator has a unique, vibrant color
- **Responsive Design**: Clean and modern interface
- **Order of Operations**: Follows PEMDAS rules (multiplication/division before addition/subtraction)

## 🛠️ Technologies Used

- **HTML5**: Structure and layout
- **CSS3**: Styling and visual design
- **Vanilla JavaScript**: Calculator logic and functionality
- **Google Fonts**: Open Sans and Roboto Slab fonts

## 📁 Project Structure

```
calculator-master/
├── index.html          # Main HTML file with calculator UI
├── script.js           # JavaScript logic for calculations
├── CSS/
│   └── style.css      # Styling for the calculator
├── preview.png        # Preview image
└── README.md          # Project documentation
```

## 🎯 How to Run

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd calculator-master
   ```

2. **Open the application**
   - Simply open `index.html` in your web browser
   - Or use a local development server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx http-server
     ```

3. **Start calculating!**
   - Click on numbers to input values
   - Click on operators to perform calculations
   - Press = to see the result

## 💡 Usage

1. **Basic Calculations**: Click numbers and operators in sequence, then press "=" to get the result
2. **Clear Entry (CE)**: Remove the current number without clearing the entire calculation
3. **Clear All (C)**: Reset the calculator completely
4. **Percentage**: Click the "%" button after a number to convert it to a percentage (divides by 100)

### Example Calculations:
- `5 + 3 × 2 =` → Result: `11` (follows order of operations)
- `50 % =` → Result: `0.5` (50 divided by 100)
- `10 ÷ 2 + 3 =` → Result: `8`

## 🎨 Key Features

### Input Validation
The calculator includes robust input validation to prevent invalid expressions:
- Prevents consecutive operators
- Ensures proper number formatting
- Alerts users when invalid input is detected

### Order of Operations
The calculator correctly implements the order of operations:
1. Percentage calculations
2. Multiplication and division (left to right)
3. Addition and subtraction (left to right)

### Color-Coded Operators
Each operator button has a unique color for better visual recognition:
- Purple (%) for percentage
- Orange (÷) for division
- Yellow (×) for multiplication
- Blue (-) for subtraction
- Pink (+) for addition
- Gray (=) for equals

## 🔮 Future Enhancements

- [ ] Add decimal point functionality
- [ ] Implement keyboard support for number and operator input
- [ ] Add memory functions (M+, M-, MR, MC)
- [ ] Include scientific calculator mode
- [ ] Add calculation history log
- [ ] Implement dark/light theme toggle
- [ ] Add support for parentheses in expressions
- [ ] Include square root and power functions
- [ ] Add animations for button clicks
- [ ] Implement responsive design for mobile devices

## 👤 Author

**Ritesh Patel**

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
