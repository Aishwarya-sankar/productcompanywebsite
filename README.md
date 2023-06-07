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
Developed By: Aishwarya S
Register No: 212222100003
```
## layout.css
```
{
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
  background-image: url("/static/img/bg.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 120px;
  color: red;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #5bb045;
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
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
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
  display: block;
  width: 100%;
  height: 40px;
  background-color: #5bb045;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
```
## home.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Aishu Cosmetics PVT LTD</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/grp.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Aishu Cosmetics PVT LTD</div>
     <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="/static/img/side.png" alt="tech">
          <div class="contenttext">
           <p> our Fancy items and Cosmetics online for Women from Aishu Cosmetics PVT LTD
                         | Buy cosmetics in Whole sale| 7 Days Returns | Trend setting models | And much more</p>


            <ul>
              <li>Branded Products</li>
              <li>COD Available</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 AISHU Cosmetics PVT LTD, Developed by Aishwarya
      </div>
    </div>
  </body>
</html>
```
## products.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Aishu Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Aishu Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/c1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Dior Foundation</div>
                  <div class="itemprice">Price: Rs.2250 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/c2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">MAC Mascara</div>
                  <div class="itemprice">Price: Rs.1650 </div>
              </div>
                <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/c3.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Chanel Highlighter</div>
                  <div class="itemprice">Price: Rs.2450 </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/c4.jpg"  alt="product image">
                  </div>
                  <div class="itemname">louis vuitton lipstick</div>
                  <div class="itemprice">Price: Rs.3290</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/c5.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Rare Beauty Blush</div>
                  <div class="itemprice">Price: Rs.1450 </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/c6.jpg"  alt="product image">
                  </div>
                  <div class="itemname">HUDA Beauty eyeshadow palette</div>
                  <div class="itemprice">Price: Rs.5450  </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/c7.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Rare Beauty lipstick</div>
                  <div class="itemprice">Price: Rs.1300 </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/c8.jpg"  alt="product image">
                  </div>
                  <div class="itemname">HUDA Beauty lipstick</div>
                  <div class="itemprice">Price: Rs.2350 </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/c9.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Dior eyeshadow</div>
                  <div class="itemprice">Price: Rs.3280 </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/c10.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Chanel Lip Gloss</div>
                  <div class="itemprice">Price: Rs.1400 </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/c11.jpg"  alt="product image">
                  </div>
                  <div class="itemname">MAC lip liner</div>
                  <div class="itemprice">Price: Rs.1250</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/c12.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Rare Beauty eyeshadow</div>
                  <div class="itemprice">Price: Rs.2370 </div>
              </div>

          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Aishu Private Limited, Developed by Aishwarya.
      </div>
    </div>
  </body>
</html>
```
## people.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Aishu Cosmetics PVT LTD</title>
    <link rel="stylesheet" href="./css/layout.css">
    <link rel="icon" href="./img/icon.png" type="image/x-icon"/>
  </head>

  <body>
    <div class="container">
      <div class="banner">Aishu Cosmetics PVT LTD</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">   
          <h1>CEO of the Brand</h1>
          <div class="productitems">
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Delphine Arnault</div>
                  <div class="itemprice">President & CEO of Dior</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Selena Gomez</div>
                  <div class="itemprice">Founder & CEO of Rare Beauty</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p3.jpg" alt="product image">
                  </div>
                  <div class="itemname">Leena Nair</div>
                  <div class="itemprice">CEO of Chanel</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p4.jpg" alt="product image">
                  </div>
                  <div class="itemname">Tim Cook</div>
                  <div class="itemprice">CEO of MAC Cosmetics</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p5.jpg" alt="product image">
                  </div>
                  <div class="itemname">Huda Kattan</div>
                  <div class="itemprice">Founder & CEO of HUDA Beauty</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p6.jpg" alt="product image">
                  </div>
                  <div class="itemname">Michael Burke</div>
                  <div class="itemprice">CEO of louis vuitton</div>
              </div>

          </div>
          </div>       
      </div>
      <div class="footer">
        Copyright &#169; 2023 Aishu Cosmetics PVT LTD, Developed by Aishwarya
      </div>
    </div>
  </body>
</html>
```
## contact.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Aishu Private Limited</title>
   <link rel="stylesheet" href="./css/layout.css">
    <link rel="icon" href="./img/bg.png" type="image/x-icon">
     
  </head>

  <body>
    <div class="container">
      <div class="banner">Aishu Private Limited</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
          
            <h1>Contact Us</h1>
            <p>If you have any questions or feedback, please don't hesitate to reach out to us.</p>
    <ul>
            <li>Address: 321 , East Main Road Street, Tamilnadu , India</li>
            <li>Phone: +91 85746922431</li>
            <li>Email: contact@aishu.com</li>
    </ul>
  
<h2> Sales Inquiries</h2>

<ul><li>Interested in any of our products? Talk to our experts today</li></ul>
        <ul><li>US: +1 (855) 747 6767 || Australia: +61 1800 861 302</li></ul>
        <ul><li>UK: +44 8081 698 824 || +44 189 280 5040</li>
        <ul><li>India: +91 44 6667 8040 </li></ul>
       
        <ul><li>Using any of our products and need help? Get in touch with customer support</li>
        <ul><li>Email: sales@aishu.com | support@aishu.com |</li>
    
  </div>
   <div class="footer">
        Copyright &#192; 2023  Aishu PVT LTD, Developed by Aishwarya
      </div>
      </div>
</body>
</html>
```
## OUTPUT:
### HOME PAGE:
![Screenshot (26)](https://github.com/Aishwarya-sankar/productcompanywebsite/assets/121418444/8d8e8f1b-3cc3-4d96-adc0-0948d19ea327)
## PRODUCT PAGE:
![Screenshot (27)](https://github.com/Aishwarya-sankar/productcompanywebsite/assets/121418444/274234b1-aa9e-437a-9f92-c0c7c162fc1a)
## PEOPLE PAGE:
![Screenshot (28)](https://github.com/Aishwarya-sankar/productcompanywebsite/assets/121418444/b290f007-503e-4a97-8162-c17a848e7065)
## CONTACT PAGE:
![Screenshot (29)](https://github.com/Aishwarya-sankar/productcompanywebsite/assets/121418444/6f197dc5-681b-4112-9dcc-8d6a4cdcd000)
## SERVER OUTPUT:
![Screenshot (30)](https://github.com/Aishwarya-sankar/productcompanywebsite/assets/121418444/f3854f87-4a93-4c0b-a00b-de9737d93d67)
## HTML VALIDATOR:
![Screenshot (31)](https://github.com/Aishwarya-sankar/productcompanywebsite/assets/121418444/7f0e1902-9b0b-41ec-b28c-13cc74d32093)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
