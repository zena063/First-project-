# First-project-
This my first project using html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Adidas Store</title>
  <link rel="stylesheet" href="style2.css" />
</head>
<body>

  <header>
    <h1>Adidas Store</h1>
  </header>

  <nav>
    <a href="https://www.adidas.com/us">HOME</a>
    <a href="https://www.adidas.com/us/men">MEN</a>
    <a href="https://www.adidas.com/us/women">WOMEN</a>
    <a href="https://www.adidas.com/us/kids">KIDS</a>
    <a href="https://www.adidas.com/us/sale">SALE</a>
    <a href="https://www.adidas.com/us/new_arrivals">NEW & TRENDING</a>
  </nav>

  <!-- Image section - Replace paths with web-accessible URLs if hosting online -->
  <section>
    <img src="img1.jpg" width="371" height="400" alt="Product Image 1">
    <img src="img2.jpg" width="371" height="400" alt="Product Image 2">
    <img src="img3.jpg" width="371" height="400" alt="Product Image 3">
    <img src="img4.jpg" width="385" height="400" alt="Product Image 4">
  </section>

  <section class="video-section">
    <h2>Watch Our Promo</h2>
    <video controls>
      <source src="promo.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </section>

  <fieldset>
    <legend>Our Top Products</legend>
    <section class="products">
      <div class="product">
        <img src="shoe1.jpg" alt="Adidas Runner">
        <h3>Adidas Runner</h3>
        <p>$120</p>
      </div>
      <div class="product">
        <img src="shoe2.jpg" alt="Adidas Boost">
        <h3>Adidas Boost</h3>
        <p>$140</p>
      </div>
      <div class="product">
        <img src="shoe3.jpg" alt="Adidas VL Shoes">
        <h3>Adidas VL Shoes</h3>
        <p>$100</p>
      </div>
    </section>
  </fieldset>

  <fieldset>
    <legend>Adidas Outfit Essentials</legend>
    <section class="products">
      <div class="product"><img src="sweatshirt.jpg" alt="Sweat-Shirt"><h3>Sweat-Shirt</h3></div>
      <div class="product"><img src="pant.jpg" alt="Pant"><h3>Pant</h3></div>
      <div class="product"><img src="jacket.jpg" alt="Jacket"><h3>Jacket</h3></div>
      <div class="product"><img src="socks.jpg" alt="Socks"><h3>Socks</h3></div>
      <div class="product"><img src="shoes.jpg" alt="Shoes"><h3>Shoes</h3></div>
      <div class="product"><img src="cap.jpg" alt="Cap"><h3>Cap</h3></div>
    </section>
  </fieldset>

  <fieldset>
    <legend>Product Info</legend>
    <table border="1" style="width: 100%; text-align: center;">
      <tr><th>Product</th><th>Price</th><th>Sizes</th><th>Colors</th></tr>
      <tr><td>Jacket</td><td>$1000</td><td>S, M, L, XL</td><td>Black, White, Blue</td></tr>
      <tr><td>T-shirt</td><td>$500</td><td>S, M, L, XL</td><td>Yellow, Purple, Orange</td></tr>
      <tr><td>Shoes</td><td>$1500</td><td>37-45</td><td>Brown, Aqua, White</td></tr>
      <tr><td>Cap</td><td>$150</td><td>-</td><td>Black, White, Gray</td></tr>
      <tr><td>Pants</td><td>$650</td><td>S, M, L, XL</td><td>Green, Blue, Black</td></tr>
      <tr><td>Bag</td><td>$360</td><td>S, M, L, XL</td><td>White, Blue, Gray, Black</td></tr>
    </table>
  </fieldset>

  <fieldset>
    <legend>Sign In</legend>
    <form>
      <label>Name:</label><br>
      <input type="text" placeholder="Your name"><br><br>
      <label>Email:</label><br>
      <input type="email" placeholder="example@gmail.com"><br><br>
      <label>Password:</label><br>
      <input type="password"><br><br>
      <label>Country:</label><br>
      <select>
        <option>France</option>
        <option>Russia</option>
        <option>USA</option>
        <option>Egypt</option>
      </select><br><br>
      <label>Gender:</label><br>
      <input type="radio" name="gender" value="Male"> Male<br>
      <input type="radio" name="gender" value="Female"> Female<br><br>
      <button type="submit">Sign In</button>
    </form>
  </fieldset>

  <fieldset>
    <legend>Billing & Payment</legend>
    <form>
      <label>Full Name:</label><br><input type="text" required><br><br>
      <label>Email:</label><br><input type="email" required><br><br>
      <label>Address:</label><br><input type="text" required><br><br>
      <label>City:</label><br><input type="text" required><br><br>
      <label>Zip Code:</label><br><input type="text" required><br><br>
      <label>Country:</label><br>
      <select required>
        <option value="">--Select--</option>
        <option>Egypt</option>
        <option>USA</option>
        <option>Germany</option>
      </select><br><br>
      <label>Phone:</label><br><input type="tel" required><br><br>
      <label>Payment Method:</label><br>
      <select>
        <option>Cash</option>
        <option>Visa</option>
        <option>PayPal</option>
      </select><br><br>
      <label>Security Code:</label><br><input type="number"><br><br>
      <button type="submit">Continue to Payment</button>
    </form>
  </fieldset>

  <fieldset>
    <legend>Feedback</legend>
    <form>
      <label>Name:</label><br><input type="text" required><br><br>
      <label>Email:</label><br><input type="email" required><br><br>
      <label>Password:</label><br><input type="password" required><br><br>
      <label>Country:</label><br>
      <select required>
        <option>France</option>
        <option>Russia</option>
        <option>USA</option>
        <option>Egypt</option>
      </select><br><br>
      <label>Gender:</label><br>
      <input type="radio" name="gender" value="Male"> Male<br>
      <input type="radio" name="gender" value="Female"> Female<br><br>
      <button type="submit">Submit Feedback</button>
    </form>
  </fieldset>

  <section style="text-align: center;">
    <p><strong>To buy Adidas products:</strong> <a href="https://www.adidas.com.eg/en">Click Here</a></p>
    <p><strong>For Special Offers:</strong> <a href="https://www.adidas.com.eg/en/sale">Click Here</a></p>
    <p><a href="https://www.adidas-group.com/en/about/profile">About</a> |
       <a href="https://www.adidas-group.com/en/about/contact">Contact</a> |
       <a href="https://www.adidas-group.com/en/about/history">History</a> |
       <a href="https://www.adidas-group.com/en/about/profile">Profile</a>
    </p>
  </section>

  <footer style="text-align: center;">
    <p><strong>THANK YOU FOR YOUR TIME.</strong></p>
    <p>&copy; 2025 Adidas Store. All rights reserved.</p>
  </footer>

</body>
</html>
