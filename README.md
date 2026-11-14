

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KISAAN CONNECT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333333;
        }

        header {
            background-color: #1a237e;
            color: white;
            text-align: center;
            padding: 20px;
        }

        header h1 {
            margin: 0;
            font-size: 28px;
        }

        header p {
            margin: 5px 0 0 0;
            color: #b3e5fc;
            font-size: 15px;
        }

        nav {
            background-color: #283593;
            text-align: center;
            padding: 10px;
        }

        nav a {
            color: white;
            background-color: #3f51b5;
            text-decoration: none;
            padding: 8px 15px;
            margin: 4px;
            display: inline-block;
            border-radius: 4px;
            font-size: 14px;
            font-weight: bold;
        }

        nav a:hover {
            background-color: #1a237e;
        }

        .container {
            width: 90%;
            max-width: 900px;
            margin: 20px auto;
        }

        .box {
            padding: 20px;
            margin-bottom: 25px;
            border-radius: 8px;
            border: 1px solid #cccccc;
        }

        h2 {
            margin-top: 0;
            border-bottom: 2px solid #555555;
            padding-bottom: 5px;
            font-size: 20px;
        }

        .bg-green-1 {
            background-color: #f4fbf7;
            border-color: #c8e6c9;
        }

        .bg-green-1 h2 {
            color: #2e7d32;
            border-color: #a5d6a7;
        }

        .bg-green-2 {
            background-color: #f6fbf0;
            border-color: #dbedc8;
        }

        .bg-green-2 h2 {
            color: #33691e;
            border-color: #c5e1a5;
        }

        .bg-red-1 {
            background-color: #fff5f5;
            border-color: #ffcdd2;
        }

        .bg-red-1 h2 {
            color: #c62828;
            border-color: #ef9a9a;
        }

        .bg-red-2 {
            background-color: #fff0f0;
            border-color: #ff8a80;
        }

        .bg-red-2 h2 {
            color: #b71c1c;
            border-color: #ff8a80;
        }

        .bg-blue-1 {
            background-color: #f0f7ff;
            border-color: #bbdefb;
        }

        .bg-blue-1 h2 {
            color: #1565c0;
            border-color: #90caf9;
        }

        .bg-blue-2 {
            background-color: #edf4fc;
            border-color: #90caf9;
        }

        .bg-blue-2 h2 {
            color: #0d47a1;
            border-color: #64b5f6;
        }

        .bg-purple-blue {
            background-color: #f3f0fc;
            border-color: #d1c4e9;
        }

        .bg-purple-blue h2 {
            color: #4a148c;
            border-color: #b388ff;
        }

        .dash-card {
            display: inline-block;
            width: 28%;
            background-color: #ffffff;
            border: 1px solid #3f51b5;
            padding: 15px;
            margin: 1%;
            text-align: center;
            border-radius: 5px;
            vertical-align: top;
            box-sizing: border-box;
        }

        .dash-card h3 {
            margin: 0;
            font-size: 26px;
            color: #1a237e;
        }

        .dash-card p {
            margin: 5px 0 0 0;
            font-size: 13px;
            font-weight: bold;
            color: #555555;
        }

        .card {
            display: inline-block;
            width: 29%;
            background-color: #ffffff;
            border: 1px solid #bbbbbb;
            padding: 12px;
            margin: 1.5%;
            border-radius: 6px;
            vertical-align: top;
            box-sizing: border-box;
        }

        .card h3 {
            margin-top: 0;
            font-size: 16px;
            color: #1a237e;
            border-bottom: 1px solid #eeeeee;
            padding-bottom: 5px;
        }

        .card p {
            margin: 5px 0;
            font-size: 13px;
        }

        .farmer-profile {
            background-color: #ffffff;
            border: 1px solid #d0d7de;
            border-radius: 10px;
            padding: 20px;
            display: flex;
            gap: 20px;
            align-items: center;
            margin-top: 15px;
        }

        .profile-avatar {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            background-color: #2e7d32;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 28px;
            font-weight: bold;
        }

        .profile-info h3 {
            margin: 0 0 8px 0;
            color: #1a237e;
            font-size: 22px;
        }

        .profile-info p {
            margin: 4px 0;
            font-size: 14px;
        }

        form {
            margin-bottom: 15px;
        }

        input, select, button {
            padding: 8px;
            margin: 5px 0;
            width: 98%;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }

        button {
            background-color: #3f51b5;
            color: white;
            border: none;
            cursor: pointer;
            font-weight: bold;
            margin-top: 10px;
        }

        button:hover {
            background-color: #1a237e;
        }

        .error-msg {
            color: #d32f2f;
            font-weight: bold;
            font-size: 13px;
            margin-top: 5px;
        }

        .success-msg {
            color: #2e7d32;
            font-weight: bold;
            font-size: 13px;
            margin-top: 5px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
            background-color: #ffffff;
        }

        th, td {
            border: 1px solid #dddddd;
            padding: 8px;
            text-align: left;
            font-size: 13px;
        }

        th {
            background-color: #e8eaf6;
            color: #1a237e;
        }

        footer {
            background-color: #1a237e;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <header id="home">
        <h1>KISAAN CONNECT</h1>
        <p>Direct Platform for Farmers and Local Buyers</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#dashboard">Dashboard</a>
        <a href="#add-farmer">Add Farmer</a>
        <a href="#farmers">Farmers Directory</a>
        <a href="#availability">Add Produce</a>
        <a href="#products">Products Market</a>
        <a href="#requests">Buyer Request</a>
        <a href="#orders">Order Status</a>
    </nav>

    <div class="container">

        <!-- DASHBOARD (LIGHT BLUE) -->
        <div class="box bg-blue-1" id="dashboard">
            <h2>Live Dashboard</h2>
            <div class="dash-card">
                <h3 id="countFarmers">7</h3>
                <p>Registered Farmers</p>
            </div>
            <div class="dash-card">
                <h3 id="countProducts">3</h3>
                <p>Available Produce</p>
            </div>
            <div class="dash-card">
                <h3 id="countOrders">0</h3>
                <p>Buyer Requests</p>
            </div>
        </div>

        <!-- ADD FARMER FORM  -->
        <div class="box bg-red-1" id="add-farmer">
            <h2>Register New Farmer</h2>
            <form id="farmerForm" novalidate>
                <label>Farmer Full Name:</label>
                <input type="text" id="farmerName">

                <label>Location / City:</label>
                <input type="text" id="farmerLocation">

                <label>Main Crops / Products:</label>
                <input type="text" id="farmerCrops">

                

                <button type="submit">Register Farmer</button>
            </form>
            <p id="farmerMsg" class="error-msg"></p>
        </div>

        
            <h2>Registered Farmer Profiles</h2>
            <div id="farmersContainer">
                <div class="card">
                    <h3>Ramesh Kumar</h3>
                    <p><strong>Location:</strong> Phagwara</p>
                    <p><strong>Crops:</strong> Tomatoes, Potatoes, Onions</p>
                </div>
                <div class="card">
                    <h3>Gurpreet Singh</h3>
                    <p><strong>Location:</strong> Ludhiana</p>
                    <p><strong>Crops:</strong> Wheat, Mustard, Rice</p>
                </div>
                <div class="card">
                    <h3>Navdeep Kaur</h3>
                    <p><strong>Location:</strong> Jalandhar</p>
                    <p><strong>Crops:</strong> Carrots, Spinach, Peas</p>
                </div>
                <div class="card">
                    <h3>Harjot Singh</h3>
                    <p><strong>Location:</strong> Amritsar</p>
                    <p><strong>Crops:</strong> Cotton, Maize, Soybean</p>
                </div>
                <div class="card">
                    <h3>Amanpreet Kaur</h3>
                    <p><strong>Location:</strong> Patiala</p>
                    <p><strong>Crops:</strong> Mangoes, Guava, Bananas</p>
                </div>
            </div>
        </div>

        <!-- ADD PRODUCE FORM -->
        <div class="box bg-red-2" id="availability">
            <h2>Add Produce Listing</h2>
            <form id="produceForm" novalidate>
                <label>Select Farmer:</label>
                <select id="cropFarmer">
                    <!-- Populated dynamically -->
                </select>

                <label>Crop / Product Name:</label>
                <input type="text" id="cropName">

                <label>Quantity Available (kg):</label>
                <input type="number" id="cropQuantity">

                <label>Price per kg (INR):</label>
                <input type="number" id="cropPrice">

                

                <button type="submit">Add Produce</button>
            </form>
            <p id="produceMsg" class="error-msg"></p>

            <h3>Your Added Produce Table</h3>
            <table>
                <thead>
                    <tr>
                        <th>Crop</th>
                        <th>Farmer</th>
                        <th>Quantity (kg)</th>
                        <th>Price/kg</th>
                        <th>Quality</th>
                    </tr>
                </thead>
                <tbody id="produceList"></tbody>
            </table>
        </div>

        <!-- PRODUCTS MARKET  -->
        <div class="box bg-blue-2" id="products">
            <h2>Available Products Catalog</h2>
            <div id="productsContainer"></div>
        </div>

        <!-- BUYER REQUEST FORM -->
        <div class="box bg-green-2" id="requests">
            <h2>Buyer Request Form</h2>
            <form id="buyerForm" novalidate>
                <label>Your Name:</label>
                <input type="text" id="buyerName">

                <label>Phone Number:</label>
                <input type="text" id="buyerPhone">

                <label>Requested Product Name:</label>
                <input type="text" id="buyerProduct">

                <label>Required Quantity (kg):</label>
                <input type="number" id="buyerQuantity">

                <label>Delivery Schedule Date:</label>
                <input type="date" id="deliveryDate">

                <button type="submit">Submit Request Order</button>
            </form>
            <p id="buyerMsg" class="error-msg"></p>
        </div>

        <!-- ORDER STATUS  -->
        <div class="box bg-purple-blue" id="orders">
            <h2>Orders and Request Status</h2>
            <table>
                <thead>
                    <tr>
                        <th>Buyer Name</th>
                        <th>Phone</th>
                        <th>Product</th>
                        <th>Quantity (kg)</th>
                        <th>Delivery Date</th>
                        <th>Status</th>
                    </tr>
                </thead>
                <tbody id="orderList"></tbody>
            </table>
            <p id="emptyOrdersMsg">No buyer requests submitted yet.</p>
        </div>

    

    <footer>
        <p>@ 2026 Farmers Retail | KISAAN CONNECT</p>
    </footer>


</body> 
