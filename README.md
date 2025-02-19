<!DOCTYPE html>
<html lang="en">
<head>
  <script src="https://js.chargebee.com/v2/chargebee.js" data-cb-site="solutions-int-test" ></script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pricing Plans</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            display: flex;
            justify-content: space-between;
            width: 80%;
            max-width: 1200px;
        }
        .pricing-card {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 30%;
            padding: 30px;
            text-align: center;
            transition: transform 0.3s ease;
        }
        .pricing-card:hover {
            transform: translateY(-10px);
        }
        .pricing-card h2 {
            font-size: 24px;
            margin-bottom: 20px;
            color: #333;
        }
        .price {
            font-size: 36px;
            font-weight: bold;
            color: #4CAF50;
            margin-bottom: 20px;
        }
        .description {
            font-size: 16px;
            color: #555;
            margin-bottom: 30px;
        }
        .button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        .button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="pricing-card">
            <h2>Go Plan</h2>
            <div class="price">$20</div>
            <p class="description">Perfect for individuals just getting started. Basic features to get you going.</p>
            <a href="#" class="button">Choose Plan</a>
        </div>
        <div class="pricing-card">
            <h2>Rise Plan</h2>
            <div class="price">$40</div>
            <p class="description">Ideal for small teams. Includes advanced features to help you grow.</p>
            <a href="#" class="button">Choose Plan</a>
        </div>
        <div class="pricing-card">
            <h2>Amaze Plan</h2>
            <div class="price">$60</div>
            <p class="description">Designed for businesses that want to scale. All features included for ultimate flexibility.</p>
            <a href="#" class="button">Choose Plan</a>
        </div>
    </div>
</body>
</html>
