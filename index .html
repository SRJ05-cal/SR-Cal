<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gold Rate Calculator</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #87CEEB; /* Sky blue background */
            color: #333; /* Darker text for better readability */
        }
        .banner {
            background-color: #ffd700; /* Gold color */
            padding: 20px;
            text-align: center;
            font-size: 1.8em;
            color: black; /* Black text in the banner for contrast */
            box-shadow: 0 0 15px gold; /* Enhanced shadow effect */
            border-radius: 10px;
        }
        .live-headline {
            background-color: rgba(255, 215, 0, 0.8); /* Semi-transparent gold */
            color: black; /* Black text for visibility */
            padding: 10px;
            font-size: 1.3em;
            text-align: center;
            margin: 20px 0;
            border: 3px solid gold; /* Gold border */
            border-radius: 5px;
            animation: pulse 1.5s infinite; /* Pulse effect */
        }
        .golden-title {
            color: darkgoldenrod; /* Dark golden color for the title */
            font-size: 2.5em;
            font-weight: bold;
            text-align: center;
            margin: 20px 0;
            text-shadow: 1px 1px 2px gold; /* Shadow effect for title */
        }
        label, select, input {
            margin: 10px 0;
            display: block;
            color: red; /* Red color for the labels and options */
            font-weight: bold; /* Bold text for labels */
        }
        input {
            color: red; /* Red color for the weight input */
            border: 2px solid darkgoldenrod; /* Dark golden border for input */
            padding: 5px;
            border-radius: 5px;
        }
        button {
            margin-top: 15px;
            padding: 10px 15px;
            font-size: 1.2em;
            background-color: darkgoldenrod; /* Dark golden button */
            color: white; /* White text for button */
            border: none;
            border-radius: 5px;
            cursor: pointer;
            box-shadow: 0 0 10px gold; /* Shadow effect for button */
            transition: background-color 0.3s ease, transform 0.3s ease; /* Smooth transition */
        }
        button:hover {
            background-color: gold; /* Change button color on hover */
            transform: translateY(-2px); /* Lift effect on hover */
        }
        #result {
            margin-top: 30px;
            text-align: center; /* Center the results */
            color: goldenrod; /* Golden color for results */
            font-size: 1.5em; /* Font size for results */
            border: 2px solid goldenrod; /* Border around the results */
            padding: 20px;
            border-radius: 10px;
            background-color: rgba(255, 255, 255, 0.9); /* Slightly transparent white */
        }
        table {
            margin: 0 auto; /* Center the table */
            width: 80%; /* Width of the table */
            border-collapse: collapse; /* Merge table borders */
        }
        td {
            padding: 10px; /* Space in table cells */
            text-align: right; /* Align text to the right */
        }
        hr {
            border: 0;
            border-top: 2px solid gold; /* Gold underline */
            margin: 10px 0; /* Space around the underline */
        }
        .follow-links a {
            color: darkblue; /* Dark blue for follow links */
            text-decoration: none; /* Remove underline */
        }
        .follow-links a:hover {
            text-decoration: underline; /* Underline on hover */
        }
        .glowing-effect {
            text-shadow: 0 0 5px gold, 0 0 10px gold; /* Glowing effect */
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>

<div class="banner">
    1 Year Gold Insurance Free
</div>

<div class="live-headline">GST & HUID is mandatory</div>

<h1 class="golden-title">SR JEWELLS</h1>

<div class="current-date" id="currentDate"></div>
<div class="current-time" id="currentTime"></div>

<h2>Current Gold Rates</h2>
<div class="gold-rates">
    <p>22k Gold Rate: ₹6650 per gram</p>
    <p>18k Gold Rate: ₹5799 per gram</p>
</div>

<h2>Gold Rate Calculator</h2>

<label for="goldType">Select Gold Type:</label>
<select id="goldType">
    <option value="22k">22k</option>
    <option value="18k">18k</option>
</select>

<label for="weight">Enter Weight (grams):</label>
<input type="number" id="weight" placeholder="Weight in grams" required>

<label for="makingChargeType">Select Making Charge Type:</label>
<select id="makingChargeType">
    <option value="handmade">Handmade Chains (5.99%)</option>
    <option value="machine">Machine Chains (5.99%)</option>
    <option value="yellow">Yellow Jewellery (7.5%)</option>
    <option value="meena">Meena Jewellery (7.5%)</option>
    <option value="turkish">Turkish Jewellery (7.5%)</option>
    <option value="premiumTurkish">Premium Turkish Jewellery (8.2%)</option>
    <option value="antique">Antique Jewellery (8.5%)</option>
    <option value="premiumAntique">Premium Antique Jewellery (9.2%)</option>
    <option value="customCasting">Custom Casting Jewellery (8.5%)</option>
    <option value="availableCasting">Available Design Casting Jewellery (7.7%)</option>
</select>

<button onclick="calculateTotal()">Calculate Total</button>

<div id="result"></div>

<script>
    const goldRates = {
        '22k': 6650,
        '18k': 5799
    };

    function calculateTotal() {
        const goldType = document.getElementById('goldType').value;
        const weight = parseFloat(document.getElementById('weight').value);
        const makingChargeType = document.getElementById('makingChargeType').value;

        if (isNaN(weight) || weight <= 0) {
            alert('Please enter a valid weight.');
            return;
        }

        const goldRate = goldRates[goldType];
        const makingChargePercent = getMakingChargePercent(makingChargeType);
        
        const goldCost = goldRate * weight;
        const makingCharge = (makingChargePercent / 100) * goldCost;
        const subtotal = goldCost + makingCharge;
        const gst = 0.03 * subtotal; // 3% GST
        const totalCost = subtotal + gst;

        document.getElementById('result').innerHTML = `
            <h2>Calculation Result</h2>
            <table>
                <tr>
                    <td>Gold Cost:</td>
                    <td>₹${goldCost.toFixed(2)}</td>
                </tr>
                <tr>
                    <td>Making Charge:</td>
                    <td>₹${makingCharge.toFixed(2)}</td>
                </tr>
                <tr>
                    <td>Subtotal:</td>
                    <td>₹${subtotal.toFixed(2)}</td>
                </tr>
                <tr>
                    <td>GST (3%):</td>
                    <td>₹${gst.toFixed(2)}</td>
                </tr>
                <tr>
                    <td><hr></td>
                    <td><hr></td>
                </tr>
                <tr>
                    <td>Total Cost:</td>
                    <td>₹${totalCost.toFixed(2)}</td>
                </tr>
            </table>
        `;
    }

    function getMakingChargePercent(type) {
        const makingChargeRates = {
            'handmade': 5.99,
            'machine': 5.99,
            'yellow': 7.5,  // Changed 'darkYellow' to 'yellow'
            'meena': 7.5,
            'turkish': 7.5,
            'premiumTurkish': 8.2,
            'antique': 8.5,
            'premiumAntique': 9.2,
            'customCasting': 8.5,
            'availableCasting': 7.7
        };
        return makingChargeRates[type];
    }

    function displayCurrentDateTime() {
        const now = new Date();
        document.getElementById('currentDate').textContent = `Date: ${now.toLocaleDateString()}`;
        document.getElementById('currentTime').textContent = `Time: ${now.toLocaleTimeString()}`;
    }

    displayCurrentDateTime();
</script>

<h3 class="glowing-effect">Gold Booking Details</h3>
<p class="glowing-effect">Account Number: 50200098935100</p>
<p class="glowing-effect">IFSC Code: HDFC0009048</p>
<p class="glowing-effect">UPI ID: 7014172905@HDFCBANK</p>
<p class="glowing-effect">Bank: HDFC Bank, NAWALGARH</p>

<h3 class="glowing-effect">Contact Details</h3>
<p class="glowing-effect">Address: Near AU Small Finance Bank, Nawalgarh (333042)</p>
<p class="glowing-effect">Mobile: 7014172905</p>

<h3>Follow Us</h3>
<p class="follow-links">
    <a href="https://www.instagram.com/06srjewells?igsh=bXJzbXRuYm9pc3Zz" target="_blank">Instagram</a><br>
    <a href="https://www.facebook.com/06Tiara?mibextid=ZbWKwL" target="_blank">Facebook</a><br>
    <a href="https://wa.me/message/SGGW2N2ENYEXK1" target="_blank">WhatsApp</a>
</p>

</body>
</html>
