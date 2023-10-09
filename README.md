# Calc-repo
Mini Project using html &amp; css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<link rel="stylesheet" href="calculator.css">
<body>
    <div class="container">
        <div class="calculator">
            <form>
                <div class="display">
                    <input type="text" name="display" disabled>
                </div>
                <div>
                    <input type="button" value="AC" onclick="display.value =''" class="ac">
                    <input type="button" class="del" value="Del" onclick="display.value =display.value.toString().slice (0,-1)">
                    <input type="button" class="symbols" value="." onclick="display.value +='.'">
                    <input type="button" class="symbols" value="/" onclick="display.value +='/'">
                </div>
                <div>
                    <input type="button" class="NumpadBtns" value="7" onclick="display.value +='7'">
                    <input type="button" class="NumpadBtns" value="8" onclick="display.value +='8'">
                    <input type="button" class="NumpadBtns" value="9" onclick="display.value +='9'">
                    <input type="button" class="symbols" value="*" onclick="display.value +='*'">
                </div>
                <div>
                    <input type="button" class="NumpadBtns" value="4" onclick="display.value +='4'">
                    <input type="button" class="NumpadBtns" value="5" onclick="display.value +='5'">
                    <input type="button" class="NumpadBtns" value="6" onclick="display.value +='6'">
                    <input type="button" class="symbols" value="-" onclick="display.value +='-'">
                </div>
                <div>
                    <input type="button" class="NumpadBtns" value="1" onclick="display.value +='1'">
                    <input type="button" class="NumpadBtns" value="2" onclick="display.value +='2'">
                    <input type="button" class="NumpadBtns" value="3" onclick="display.value +='3'">
                    <input type="button" class="symbols" value="+" onclick="display.value +='+'">
                </div>
                <div>
                    <input type="button" class="special" value="00" onclick="display.value +='00'">
                    <input type="button" class="special" value="0" onclick="display.value += '0'">
                    <input type="button" value="=" onclick="display.value = eval(display.value)" class="equal">
                </div>
            </form>
        </div>
    </div>
</body>
</html>
