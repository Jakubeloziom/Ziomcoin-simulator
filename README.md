<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ziomcoin Simulator</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="header">
        <h1>Ziomcoin Simulator</h1>
        <div id="ziomcoin-counter">J: <span id="ziomcoin-amount">0</span></div>
        <div id="upgrades-button">⚡ Upgrades</div>
    </div>

    <div id="main">
        <div id="coin"></div>
    </div>

    <div id="upgrades-panel" class="hidden">
        <h2>Upgrades</h2>
        <button onclick="buyUpgrade(1)">Upgrade 1 (10 Ziomcoin)</button>
        <button onclick="buyUpgrade(2)">Upgrade 2 (50 Ziomcoin)</button>
    </div>

    <script src="script.js"></script>
</body>
</html>
