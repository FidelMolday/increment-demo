vanila javascript program
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Increment Button</title>
</head>
<body>
    <button id="increment-btn">+1</button>
    <div id="count-display">1</div>

    <script>
        const incrementBtn =document.getElementById("increment-btn");
        const countDisplay =document.getElementById("count-display");

        let currentCount = 0

        incrementBtn.addEventListener("click",() => {
            currentCount ++;
            countDisplay.innerText = currentCount
        })
    </script>
</body>
</html>
