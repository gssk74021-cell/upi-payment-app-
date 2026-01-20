# upi-payment-app-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>UPI Payment App</title>
  <link rel="stylesheet" href="style.css">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

  <div class="app">
    <h2>💸 UPI Pay</h2>

    <div class="input-group">
      <label>UPI ID</label>
      <input type="text" id="upi" placeholder="example@upi">
    </div>

    <div class="input-group">
      <label>Amount (₹)</label>
      <input type="number" id="amount" placeholder="Enter amount">
    </div>

    <button onclick="payNow()">Pay Now</button>

    <p id="message"></p>
  </div>

  <script src="script.js"></script>
</body>
</html>

