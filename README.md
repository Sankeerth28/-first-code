# -first-code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>All Products - Cozystore</title>
    <link rel="stylesheet" href="shopping.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body>

    <div class="container"> 
        <div class="navbar">
        <div class="logo">
            <img src="logo.png" width="125px">
        </div>
        <nav>
            <ul id="MenuItems">
                 <li><a href="shoppinghtml.html">Home</a></li>
                <li><a href="all products.html">Products</a></li>
                <li><a href="">About</a></li>
                <li><a href="">Contact</a></li>
                <li><a href="accounts.html">Account</a></li>
            </ul>
        </nav>
        <a href="CARTT.html"><img src="cart.png" width="30px" height="30px"></a>
        <img src="menu.png" class="menu-icon" onclick="menutoggle()">
    </div>
</div>
<!-------cart items details----->
<div class="small-container cart-page">
    <table>
        <tr>
            <th>Product</th>
            <th>Quantity</th>
            <th>Subtotal</th>
        </tr>
        <tr>
            <td>
                <div class="cart-info">
                    <img src="buy-1.jpg">
                    <div>
                        <p>Red Printed T-Shirt</p>
                        <small>Price: ₹500</small>
                        <br>
                        <a href="">Remove</a>
                    </div>
                </div>
            </td>
            <td><input type="number" value="1"></td>
            <td>₹500</td>
        </tr>
        <tr>
            <td>
                <div class="cart-info">
                    <img src="buy-2.jpg">
                    <div>
                        <p>Red Printed T-Shirt</p>
                        <small>Price: ₹600</small>
                        <br>
                        <a href="">Remove</a>
                    </div>
                </div>
            </td>
            <td><input type="number" value="1"></td>
            <td>₹600</td>
        </tr>
        <tr>
            <td>
                <div class="cart-info">
                    <img src="buy-3.jpg">
                    <div>
                        <p>Red Printed T-Shirt</p>
                        <small>Price: ₹700</small>
                        <br>
                        <a href="">Remove</a>
                    </div>
                </div>
            </td>
            <td><input type="number" value="1"></td>
            <td>₹700</td>
        </tr>
    </table>
        <div class="total-price">
        <table>
            <tr>
                <td>Subtotal</td>
                <td>₹1800</td>
            </tr>
            <tr>
                <td>Tax</td>
                <td>₹100</td>
            </tr>
            <tr>
                <td>Total</td>
                <td>₹1900</td>
            </tr>
        </table>
    </div>
</div>
<!------footer------>
  <div class="footer">
    <div class="container">
        <div class="row">
            <div class="footer-col-1">
                <h3>Download Our App</h3>
                <p>Download App for Android and ios mobile phone. </p>
                <div class="app-logo">
                    <img src="play-store.png">
                    <img src="app-store.png">
                </div>
            </div>
            <div class="footer-col-2">
                <img src="logo-white.png">
                <p>Our Purpose Is To Sustainably Make the Pleasure and Benefits of Comfortable Accesible to the Many.</p>
            </div>
             <div class="footer-col-3">
                <h3>Useful Links</h3>
                <ul>
                    <li>Coupons</li>
                    <li>Blog Post</li>
                    <li>Return Policy</li>
                    <li>Join Affiliate</li>
                </ul>
            </div>
            <div class="footer-col-4">
                <h3>Follow us</h3>
                <ul>
                    <li>Facebook</li>
                    <li>Twitter</li>
                    <li>Instagram</li>
                    <li>YouTube</li>
                </ul>
            </div>
        </div>
        <hr>
        <p class="copyright">Copy right - REDSTORE</p>
    </div>
  </div>
  <!-----js for toggle menu------>
  <script>
    var MenuItems = document.getElementById("MenuItems");

    MenuItems.style.maxHeight = "0px";
    
    function menutoggle(){
        if( MenuItems.style.maxHeight == "0px")
        {
            MenuItems.style.maxHeight = "200px"; 
        }
        else
        {
            MenuItems.style.maxHeight = "0px";
        }
        
    }
  </script>

</body>
</html> s
