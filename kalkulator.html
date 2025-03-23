<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalkulator Web</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f4f4f4;
        }
        .calculator {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .display {
            width: 100%;
            height: 50px;
            font-size: 2em;
            text-align: right;
            margin-bottom: 10px;
            border: none;
            padding: 10px;
            background: #eaeaea;
        }
        .buttons {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 10px;
        }
        button {
            font-size: 1.5em;
            padding: 15px;
            border: none;
            background: #007BFF;
            color: white;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background: #0056b3;
        }
        .clear {
            background: #dc3545;
        }
        .clear:hover {
            background: #a71d2a;
        }
    </style>
</head>
<body>
    <div class="calculator">
        <input type="text" class="display" disabled>
        <div class="buttons">
            <button class="number">7</button>
            <button class="number">8</button>
            <button class="number">9</button>
            <button class="operation">/</button>
            <button class="number">4</button>
            <button class="number">5</button>
            <button class="number">6</button>
            <button class="operation">*</button>
            <button class="number">1</button>
            <button class="number">2</button>
            <button class="number">3</button>
            <button class="operation">-</button>
            <button class="number">0</button>
            <button class="clear">C</button>
            <button class="equals">=</button>
            <button class="operation">+</button>
            <button class="operation">^</button>
            <button class="operation">√</button>
            <button class="operation">%</button>
            <button class="operation">sin</button>
        </div>
    </div>

    <script>
        class Calculator {
            constructor() {
                this.currentValue = '';
                this.previousValue = '';
                this.operation = null;
            }

            clear() {
                this.currentValue = '';
                this.previousValue = '';
                this.operation = null;
            }

            appendNumber(number) {
                this.currentValue += number;
            }

            chooseOperation(operation) {
                if (operation === '√') {
                    if (this.currentValue === '') return;
                    this.currentValue = Math.sqrt(parseFloat(this.currentValue));
                    return;
                }
                if (operation === '%') {
                    if (this.currentValue === '') return;
                    this.currentValue = parseFloat(this.currentValue) / 100;
                    return;
                }
                if (operation === 'sin') {
                    if (this.currentValue === '') return;
                    this.currentValue = Math.sin(parseFloat(this.currentValue) * (Math.PI / 180));
                    return;
                }
                if (this.currentValue === '') return;
                if (this.previousValue !== '') {
                    this.compute();
                }
                this.operation = operation;
                this.previousValue = this.currentValue;
                this.currentValue = '';
            }

            compute() {
                let result;
                const prev = parseFloat(this.previousValue);
                const current = parseFloat(this.currentValue);
                if (isNaN(prev) || isNaN(current)) return;

                switch (this.operation) {
                    case '+':
                        result = prev + current;
                        break;
                    case '-':
                        result = prev - current;
                        break;
                    case '*':
                        result = prev * current;
                        break;
                    case '/':
                        result = prev / current;
                        break;
                    case '^':
                        result = Math.pow(prev, current);
                        break;
                    default:
                        return;
                }

                this.currentValue = result;
                this.operation = null;
                this.previousValue = '';
            }
        }

        const calculator = new Calculator();

        function updateDisplay() {
            document.querySelector('.display').value = calculator.currentValue;
        }

        document.addEventListener('DOMContentLoaded', () => {
            document.querySelectorAll('.number').forEach(button => {
                button.addEventListener('click', () => {
                    calculator.appendNumber(button.innerText);
                    updateDisplay();
                });
            });

            document.querySelectorAll('.operation').forEach(button => {
                button.addEventListener('click', () => {
                    calculator.chooseOperation(button.innerText);
                    updateDisplay();
                });
            });

            document.querySelector('.equals').addEventListener('click', () => {
                calculator.compute();
                updateDisplay();
            });

            document.querySelector('.clear').addEventListener('click', () => {
                calculator.clear();
                updateDisplay();
            });
        });
    </script>
</body>
</html>
