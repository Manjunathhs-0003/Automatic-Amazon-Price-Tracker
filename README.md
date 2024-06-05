<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>Amazon Price Tracker</h1>

<p>This script tracks the price of a product on Amazon and sends an email alert when the price drops below a specified value.</p>

<h2>Features</h2>
<ul>
    <li>Fetches the product's current price and title from Amazon.</li>
    <li>Compares the current price with a predefined target price.</li>
    <li>Sends an email alert if the current price is below the target price.</li>
</ul>

<h2>Requirements</h2>
<ul>
    <li>Python 3.x</li>
    <li><code>requests</code></li>
    <li><code>beautifulsoup4</code></li>
    <li><code>lxml</code></li>
    <li><code>smtplib</code></li>
</ul>

<h2>Setup</h2>

<ol>
    <li><strong>Clone the repository:</strong>
    <pre>
<code>
git clone https://github.com/Manjunathhs-0003/Automatic-Amazon-Price-Tracker.git
cd amazon-price-tracker
</code>
    </pre>
    </li>

    <li><strong>Install required packages:</strong>
    <pre>
<code>
pip install requests beautifulsoup4 lxml
</code>
    </pre>
    </li>

  <li><strong>Set up environment variables:</strong>
    <p>Replace the placeholders <code>YOUR_SMTP_ADDRESS</code>, <code>YOUR_EMAIL</code>, and <code>YOUR_PASSWORD</code> with your SMTP server address, your email address, and your email password, respectively.</p>
    <pre>
<code>
YOUR_SMTP_ADDRESS = "your_smtp_address"
YOUR_EMAIL = "your_email"
YOUR_PASSWORD = "your_password"
</code>
    </pre>
    </li>

  <li><strong>Update the script with the product URL and buying price:</strong>
    <p>Replace <code>ENTER THE PRODUCTS URL HERE</code> with the URL of the Amazon product you want to track. Set the <code>BUY_PRICE</code> to your target price.</p>
    <pre>
<code>
url = "ENTER THE PRODUCTS URL HERE"
BUY_PRICE = 200  # Set the buying price to track the changes in price
</code>
    </pre>
    </li>
</ol>

<h2>Usage</h2>
<p>Run the script to start tracking the price:</p>
<pre>
<code>
python price_tracker.py
</code>
</pre>

</body>
</html>
