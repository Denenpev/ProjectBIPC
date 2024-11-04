<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <link rel="stylesheet" href="style.css"/>
        <title>Order Form</title>
    </head>
    <body
        <div class="container">
            <h1>Bipc Company Order Form</h1>
            <form id="Order-form">
                <div class="section">
                <label for="CompanyName">Company Name:</label>
                <input type="text" id="CompanyName"Name="CompanyName" required><br><br>
                </div>
                <div class="section">
                    <label for="contactName">Contact Name:</label>
                    <input type="text"id="contactName" name="contactName"required>
                </div>
                <div class="section">
                    <label for="Address">Address:</label>
                    <input type="text"id="address" name="address"required>
                </div>
                <div class="section">
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="section">
                    <label for="phoneNumber">phone Number:</label>
                    <input type="tel" id="phoneNumber" name="phoneNumber"required>
                </div>
                <div class="section">
                    <label for="OrderItems">Order Items</label><br>
                    <input type="checkbox"id="bread"name="bread" required>
                </div>
                <div class="section">
                    <label for="bread">Bread (1100)</label><br>
                    <input type="number" id="breadQuantity"name="breadQuantity" placeholder="Quantity"><br>
                    <input type="checkbox" id="yamFlour"name="yamFlour"><br>
                </div>
                <div class="section">
                    <label for="yamFlour">Yam Flour (2500)</label><br>
                    <input type="number" id="yamFlourQuantity"name="yamFlourQuantity" placeholder="Quantity"><br>
                    <input type="checkbox" id="water"name="water">
                </div>
                <div class="section">
                    <label for="water">Water (300)</label><br>
                    <input type="number" id="waterQuantity"name="waterQuantity" placeholder="Quantity"><br><br>
                </div>
                <div class="section">
                    <input type="button" oneclick="calculate()" value="calculate Total">
                    <input type="submit" value="place Order">
                </div>
            </form>
        </div>
    </body>
</html>
