# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```
Hompage Coding:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>E-MART Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon2.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">E-MART Limited</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/book.png" alt="Image" />
          <div class="contenttext">
            Welcome to E-MART Limited!
             E-MART is an online bookstore with a mission to financially support local, 
             independent bookstores.
             We believe that bookstores are essential to a healthy culture. 
             They’re where authors can connect with readers, 
             where we discover new writers, where children get hooked on the thrill of 
             reading that can last a lifetime. They’re also anchors for our downtowns and communities.
            <br />
            We hope that Bookshop can help strengthen the fragile ecosystem and margins around bookselling 
            and keep local bookstores an integral part of our culture and communities.
            Bookshop is a benefit corporation - a corporation dedicated to the public good.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Note worthy books </li>
              <li>Anywhere, anytime access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Sudharshna Lakshmi.S
      </div>
    </div>
  </body>
</html>

Product Coding:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>E-MART Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon2.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">E-MART Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>  
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/1.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price:Rs.10,000</div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/2.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price:Rs.8999</div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/3.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Special Edition</div>
                  <div class="itemprice">Price: Rs.7599 </div>
              </div>

              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/4.png"  alt="product image">
                </div>
                <div class="itemname">Tally Nine</div>
                <div class="itemprice">Price: 5599 </div>
            </div>

            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/5.png"  alt="product image">
              </div>
              <div class="itemname">Novel</div>
              <div class="itemprice">Price: Rs.700.00 </div>
          </div>

          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/6.png"  alt="product image">
            </div>
            <div class="itemname">Story Book + CD</div>
            <div class="itemprice">Price: Rs.859 </div>
        </div>

        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/7.png"  alt="product image">
          </div>
          <div class="itemname">Grammar Book</div>
          <div class="itemprice">Price: Rs.500.00 </div>
      </div>

      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/8.png"  alt="product image">
        </div>
        <div class="itemname"></div>
        <div class="itemprice">Price: Rs.759 </div>
    </div>

    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/9.png"  alt="product image">
      </div>
      <div class="itemname">HTML + Java(comb0)</div>
      <div class="itemprice">Price: Rs.1999 </div>
    </div>

    <div class="productitem"> 
       <div class="itemimage">
       <img src="/static/img/10.png"  alt="product image">
       </div>
       <div class="itemname">Easy Way to Learn Hindi</div>
       <div class="itemprice">Price: Rs.2229.00 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/11.png"  alt="product image">
    </div>
       <div class="itemname">Tamil to English Translater </div>
       <div class="itemprice">Price: Rs.789 </div>
    </div>

    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/12.png"  alt="product image">
     </div>
        <div class="itemname">Telugu Dictionary</div>
        <div class="itemprice">Price: Rs.2559 </div>
      </div>
    </div>
  </div>        
  </div>
    <div class="footer">
      Copyright &#169; 2021 EduSoft Private Limited, Developed by Sudharshna Lakshmi.S
    </div>
  </div>
 </body>
</html>

People Coding:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>E-MART Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon2.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">E-MART Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitemselected"><a href ="/static/people.html"></a>People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/1.jpg"  alt="product image">
      </div>
         <div class="itemname">HEAD of the company
           <br>
           (Diana)
         </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/2.jpg"  alt="product image">
      </div>
         <div class="itemname">Manager
           <br>
           (Selvi)
         </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/3.jpg"  alt="product image">
      </div>
         <div class="itemname">Assistant class <br>(Berry)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/4.jpg"  alt="product image">
      </div>
         <div class="itemname">Product Department Head <br> (Jhon)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/5.jpg"  alt="product image">
      </div>
         <div class="itemname">Deliver Department Head <br> (Lakshmi)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/6.jpg"  alt="product image">
      </div>
         <div class="itemname">Chennai Branch Head <br> (Dev)</div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Sudharshna Lakshmi.S
      </div>
    </div>
  </body>
</html>

Contact Coding:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>E-MART Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon2.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">E-MART Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      
        <div class="contact content">
           <h1>Our Contact Address</h1>  
        
          <div class="contacttext">
           Phone:6592001799
           <br>Eamail-address:e-martlimited@eemail.com
          </div>
        </div>

     
<div class="footer">
  Copyright &#169; 2021 EduSoft Private Limited, Developed by Sudharshna Lakshmi.S
</div>
</div>
</body>
</html>

layout.css:

* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/banner2.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: black;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color:black;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color:rgb(114, 14, 114);
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color:white;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: inline-block;
  width: 100%;
  height: 40px;
  background-color:black;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}

.contact content{
  display: block;
  width: 100%;
  background-color:white;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.contacttext{
  text-align: justify;
  font-style: normal;
  font-size: larger;
}
.people content{
  display: block;
  width: 100%;
  background-color:white;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}

```

## OUTPUT:

### Home Page:

![output](./images/Homepage.PNG)

### Product:
![output](./images/Products.PNG)

### People:

![output](./images/People.PNG)

### Contact Us:

![output](./images/Contactus.PNG)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
