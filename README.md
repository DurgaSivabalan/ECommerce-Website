# ECommerce-Website
html>

<head>
    <title>E-Commerce</title>
    <style>
        body{
background-color: white;
        }
       header
{
background-color: burlywood;
color:black;
}
header h2
{
    text-align: left;
    padding-top: 10px;
    color: black;
}
a{
text-decoration: none;
color:black;
margin:5px;
text-align: right;
justify-content: right;
}
#product
{
    display: flex;
    justify-content: space-around;
}
.product1
{
    text-align: center;
    justify-content: center;
    border:1px solid black;
    margin:40px;
    padding:10px;

}
button{
    background-color: white;
    border-radius: 10px;
    padding:10px;
    color:black;
}
button:hover{
    background-color:black;
    color:white;
}
footer{
    padding-top: 75px;
    text-align: center;
    font-size: 20px;
    font-weight: bold;
   

}
    </style>
</head>

<body>
    <header>
        <h2>Shopping mart</h2>
        <a href="C:\Users\durga\OneDrive\Desktop\icon.html">HOME</a>
        <a href="C:\Users\durga\OneDrive\Desktop\icon.html">ABOUT</a>
        <a href="C:\Users\durga\OneDrive\Desktop\icon.html">SERVICE</a>
        <a href="C:\Users\durga\OneDrive\Desktop\icon.html">CONTACT</a>
    </header>
    <div id="product">
    <div class="product1">
        <img src="C:\Users\durga\OneDrive\Desktop\Web\images\shirt" style="height: 200px;width: 200px;" />
        <h3>Rayon shirts</h3>
        <p><s>RS.1000</s> Rs.850<br><mark>20% discount</mark></p>
        <button>Add to cart</button>
    </div>
    <div class="Product1">
        <img src="C:\Users\durga\OneDrive\Desktop\Web\images\shoe.jpg" style="height: 200px;width: 200px;">
        <h3>Trendy Shoes</h3>
        <p><s>RS.1999</s> Rs.1500<br><mark>25% discount</mark></p>
        <button>Add to cart</button>

    </div>
    <div class="Product1">
        <img src="C:\Users\durga\OneDrive\Desktop\Web\images\kurti.webp" style="height: 200px;width: 200px;"">
        <h3>Classical Kurtis</h3>
        <p><s>RS.890</s> Rs.700<br><mark>20% discount</mark></p>
        <button>Add to cart</button>

    </div>
    </div>
    <footer>&copy;Copyrights should be reseved by Own</footer>
</body>

</html>
