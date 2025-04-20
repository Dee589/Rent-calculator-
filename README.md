<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rent Calculator</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="calculator-container">
    <h1>Rent Calculator</h1>
    <form id="rent-form">
      <label for="total-rent">Total Rent ($):</label>
      <input type="number" id="total-rent" placeholder="Enter total rent" required>
      
      <label for="roommates">Number of Roommates:</label>
      <input type="number" id="roommates" placeholder="Enter number of roommates" required>
      
      <button type="button" id="calculate-btn">Calculate</button>
    </form>
    <div id="result" class="result"></div>
  </div>
  <script src="script.js"></script>
</body>
</html># Rent-calculator-
