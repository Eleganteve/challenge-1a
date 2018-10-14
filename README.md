IN +49.1 KB UI/images/cake.jpeg
Binary file not shown.
BIN +20.7 KB UI/images/candy.jpg
Binary file not shown.
BIN +19.3 KB UI/images/biscuit-.jpg
Binary file not shown.
2 UI/static/login.css
@@ -7,7 +7,7 @@ body {
	height: 100vh;
	background-size: cover;
	background-position: center;
	background-image: url("../images/bg.png");
	background:#a7aab1;
	
}
11 UI/static/pdts.css
@@ -1,15 +1,16 @@
body{
	background-image: url("../images/bg.png");
	background: #457;
	background-size: cover;
	background-repeat: no-repeat;
}
.product {
	width: 400px;
	margin: auto;
	padding: 5px 0px;
	width: 30%;
	margin: 10px;
	padding: 1px 0px;
	display: inline-block;
}
 
@@ -18,7 +19,7 @@ h4 {
	font-weight: normal;
	margin: 0; 
	font-size: 16pt;
	color: #aaa; }
	color: #000; }
 
	figure img { max-width: 150px;
	}
2 UI/templates/index.html
@@ -24,7 +24,7 @@
      <form class="login-form">
        <input type="text" name="" placeholder="user name">
        <input type="text" name="" placeholder="password">
        <button><a href="products.html"> Create </a> </button> 
        <button><a href="product.html"> Create </a> </button> 
        <p class="message"> Not Registered? <a href="Register.html">Register </a></p>
      </form>
    </div>
135 UI/templates/product.html
@@ -0,0 +1,135 @@
<!DOCTYPE html>
<html>
<head>
  <title></title>
  <link rel="stylesheet" type="text/css" href="../static/pdts.css">
  <link rel="stylesheet" type="text/css" href="../static/login.css">
  <style>
    
  </style>
</head>
<body> 
  <nav>
    <div class="navbar">
  <a href="#home">Store Manager</a>
  <button onclick="document.getElementById('id01').style.display='block'" style="width:auto;">Login</button>
  <button onclick="document.getElementById('id01').style.display='block'" style="width:auto;background-color: #ccc;color: #000;">Admin Login</button>
</div>
  </nav>
  <div class="product clear" style="margin: 30px;">
      <header>
          <h4 style="margin-left: -250px;margin-bottom: 20px;">Chocolate cake</h4>
      </header>
      <figure>
        <a href="singlepdt.html"><img src="../images/chocolate.jpg"></a>
      <div>Quantity
          <select>
            <option value="quantity">1</option>
            <option value="quantity">2</option>
            <option value="quantity">3</option>
            <option value="quantity">4</option>
            <option value="quantity">5</option>
          </select>
        </div>
        <button style="width: 40%; float: left;">Buy Now</button> 
      </figure>
    </div>
    <div class="product clear" style="margin: 10px;">
      <header>
          <h4 style="margin-left: -250px;margin-bottom: 20px;">Chocolate cake</h4>
      </header>
      <figure>
        <a href="singlepdt.html"><img src="../images/chocolate.jpg"></a>
      <div>Quantity
          <select>
            <option value="quantity">1</option>
            <option value="quantity">2</option>
            <option value="quantity">3</option>
            <option value="quantity">4</option>
            <option value="quantity">5</option>
          </select>
        </div>
        <button style="width: 40%; float: left;">Buy Now</button> 
      </figure>
 </div>
 <div class="product clear" style="margin: 10px;">
      <header>
          <h4 style="margin-left: -250px;margin-bottom: 20px;">Chocolate cake</h4>
      </header>
      <figure>
        <a href="singlepdt.html"><img src="../images/chocolate.jpg"></a>
      <div>Quantity
          <select>
            <option value="quantity">1</option>
            <option value="quantity">2</option>
            <option value="quantity">3</option>
            <option value="quantity">4</option>
            <option value="quantity">5</option>
          </select>
        </div>
        <button style="width: 40%; float: left;">Buy Now</button> 
      </figure>
    </div>
    <div class="product clear" style="margin: 30px;">
      <header>
          <h4 style="margin-left: -250px;margin-bottom: 20px;">Chocolate cake</h4>
      </header>
      <figure>
        <a href="singlepdt.html"><img src="../images/chocolate.jpg"></a>
      <div>Quantity
          <select>
            <option value="quantity">1</option>
            <option value="quantity">2</option>
            <option value="quantity">3</option>
            <option value="quantity">4</option>
            <option value="quantity">5</option>
          </select>
        </div>
        <button style="width: 40%; float: left;">Buy Now</button> 
      </figure>
 </div>
 <div class="product clear" style="margin: 10px;">
      <header>
          <h4 style="margin-left: -250px;margin-bottom: 20px;">Chocolate cake</h4>
      </header>
      <figure>
        <a href="singlepdt.html"><img src="../images/chocolate.jpg"></a>
      <div>Quantity
          <select>
            <option value="quantity">1</option>
            <option value="quantity">2</option>
            <option value="quantity">3</option>
            <option value="quantity">4</option>
            <option value="quantity">5</option>
          </select>
        </div>
        <button style="width: 40%; float: left;">Buy Now</button> 
      </figure>
    </div>
    <div class="product clear" style="margin: 10px;">
      <header>
          <h4 style="margin-left: -250px;margin-bottom: 20px;">Chocolate cake</h4>
      </header>
      <figure>
        <a href="singlepdt.html"><img src="../images/chocolate.jpg"></a>
      <div>Quantity
          <select>
            <option value="quantity">1</option>
            <option value="quantity">2</option>
            <option value="quantity">3</option>
            <option value="quantity">4</option>
            <option value="quantity">5</option>
          </select>
        </div>
        <button style="width: 40%; float: left;">Buy Now</button> 
      </figure>
 </div>
    
  <footer>
    <h4>Anything goes for now</h4>
</footer>
</body>
</html>
