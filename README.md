# Calculator
I created a calculator using html ,CSS, JS.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Calculator</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Orbitron&display=swap">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="calculator">
        <input type="text" id="display" readonly>
        <div class="buttons">
            <button onclick="clearDisplay()">C</button>
            <button onclick="deleteLast()">DEL</button>
            <button onclick="appendCharacter('/')">/</button>
            <button onclick="appendCharacter('*')">*</button>
            <button onclick="appendCharacter('7')">7</button>
            <button onclick="appendCharacter('8')">8</button>
            <button onclick="appendCharacter('9')">9</button>
            <button onclick="appendCharacter('-')">-</button>
            <button onclick="appendCharacter('4')">4</button>
            <button onclick="appendCharacter('5')">5</button>
            <button onclick="appendCharacter('6')">6</button>
            <button onclick="appendCharacter('+')">+</button>
            <button onclick="appendCharacter('1')">1</button>
            <button onclick="appendCharacter('2')">2</button>
            <button onclick="appendCharacter('3')">3</button>
            <button onclick="calculate()">=</button>
            <button onclick="appendCharacter('0')">0</button>
            <button onclick="appendCharacter('.')">.</button>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>

