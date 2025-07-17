<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Cart Option</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
    }

    .cart-container {
      position: relative;
      display: inline-block;
      cursor: pointer;
    }

    .cart-icon {
      font-size: 28px;
      color: #333;
    }

    .cart-count {
      position: absolute;
      top: -8px;
      right: -10px;
      background: red;
      color: white;
      font-size: 14px;
      padding: 2px 6px;
      border-radius: 50%;
    }
  </style>
</head>
<body>

<!-- Cart Icon -->
<div class="cart-container">
  <i class="fas fa-shopping-cart cart-icon"></i>
  <span class="cart-count">2</span>
</div>

</body>
</html>
