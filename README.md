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
css layout
```
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
  background-image: url("/static/img/adobe.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #16d1ae;
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
  produdts.html
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
  home
  ```
  <!DOCTYPE html>
<html lang="en">
  <head>
    <title></title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/ss.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Sameer.s.
      </div>
    </div>
  </body>
</html>
```
products
```
<!DOCTYPE html>
<html lang="en">
<head>
<title></title>
<link rel="stylesheet" href="./css/layout.css" />
<link rel="icon" href="./img/icon.png" type="image/x-icon" />
</head>
<body>
<div class="container">
<div class="banner"></div>
<div class="menu">
<div class="menuitem"><a href="/static/home.html">Home</a></div>
<div class="menuitemselected"><a href="/static/products.html">Products</a></div>
<div class="menuitem"><a href="/static/people.html">People</a></div>
<div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
</div>
<div class="content">
<div class="productcontent">
<h1>Our Premium Products</h1>
<div class="productitems">
<div class="productitem">
<div class="itemimage">
<img src="/static/img/s4.png" alt="product image">
</div>
<div class="itemname">Adobe after filter</div>
<div class="itemprice">Price: Rs.4000 </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/s5.jfif" alt="product image">
</div>
<div class="itemname">adobe fresco</div>
<div class="itemprice">Price: Rs.4500 </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/s6.png" alt="product image">
</div>
<div class="itemname">adobe Dimenssions</div>
<div class="itemprice">Price: Rs.5000 </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/s7.jfif" alt="product image">
</div>
<div class="itemname">adobe Substance</div>
<div class="itemprice">Price: Rs.5500 </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/s8.png" alt="product image">
</div>
<div class="itemname">adobe Dreeamweaver</div>
<div class="itemprice">Price: Rs.6000 </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/s10.png" alt="product image">
</div>
<div class="itemname">adobe Illustrator</div>
<div class="itemprice">Price: Rs.6500</div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/s11.png" alt="product image">
</div>
<div class="itemname">adobe indesign cc</div>
<div class="itemprice">Price: Rs.7000 </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/s12.png" alt="product image">
</div>
People.html
<div class="itemname">adob lightroom</div>
<div class="itemprice">Price: Rs.7500 </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/s13.png" alt="product image">
</div>
<div class="itemname">adobeb lightroom</div>
<div class="itemprice">Price: Rs.8000 </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/s14.png" alt="product image">
</div>
<div class="itemname">adobe premier pro</div>
<div class="itemprice">Price: Rs.9000 </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/s15.png" alt="product image">
</div>
<div class="itemname">adobeb rush</div>
<div class="itemprice">Price: Rs.9500 </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/s16.png" alt="product image">
</div>
<div class="itemname">adobeb spark</div>
<div class="itemprice">Price: Rs.10,000 </div>
</div>
</div>
</div>
</div>
</div>
<div class="footer">
Copyright &#169; 2021 EduSoft Private Limited, Developed by Sameer.S.
</div>
</div>
</body>
</html>
```
people
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>adobe </title>
<link rel="stylesheet" href="./css/layout.css" />
<link rel="icon" href="./img/ail.png" type="image/x-icon" />
</head>
<body>
<div class="container">
<div class="banner"></div>
<div class="menu">
<div class="menuitem"><a href="/static/home.html">Home</a></div>
<div class="menuitem"><a href="/static/products.html">Products</a></div>
<div class="menuitem"><a href="/static/people.html">People</a></div>
<div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a>
</div>
</div>
<div class="content">
<div class="homecontent">
<h1>Our company employees:</h1><br><br>
<div class="productitems">
<div class="productitem">
<div class="itemimage">
<img src="/static/img/guna.jpeg" alt="product image">
</div>
<div class="itemname">Gunasekhar</div>
<div class="itemprice">CEO </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/s.jpeg" alt="product image">
</div>
<div class="itemname">Sameer</div>
<div class="itemprice">DSM</div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/s1.jfif" alt="product image">
</div>
<div class="itemname">Ashwini</div>
<div class="itemprice">Assistant HR </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/s3.jpg" alt="product image">
</div>
<div class="itemname">Jeeva</div>
<div class="itemprice">HR </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/s9.jfif" alt="product image">
</div>
<div class="itemname">Krishna</div>
<div class="itemprice">RSM </div>
</div> <div class="productitem">
<div class="itemimage">
<img src="/static/img/s18.png" alt="product image">
</div>
contact.html
<div class="itemname">Vasib</div>
<div class="itemprice">senior manager</div>
</div>
</div>
</div>
</div>
</div>
<div class="footer">
Copyright &#169; 2021 Adobe Private Limited, Developed by Sameer.S.
</div>
</div>
</body>
</html>
```
contactus
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Adobe</title>
<link rel="stylesheet" href="./css/layout.css" />
<link rel="icon" href="./img/ail.png" type="image/x-icon" />
</head>
<body>
<div class="container">
<div class="banner"></div>
<div class="menu">
<div class="menuitem"><a href="/static/home.html">Home</a></div>
<div class="menuitem"><a href="/static/products.html">Products</a></div>
<div class="menuitem"><a href="/static/people.html">People</a></div>
<div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a>
</div>
</div>
<div class="content">
<div class="homecontent">
<h1>Contact Us:</h1><br><br>
<h1>Address:</h1>
<div class="contenttext">
967/4 G.I.D.C., MAKARPURA, VADODARA 390010, GUJARAT, INDIA.
</div><br>
<h1>Phone:</h1><br>
<div class="contenttext">
Mr.gunasekhar(HR):6303363975<br><br>
Mr.Tharun(Assistant HR):9573819022
</div>
<h1>E-Mail:</h1><br>
<div class="contenttext">
Sales:shaiksameer6056@gmail.com
</div>
</div>

</div>
<div class="footer">
Copyright &#169; 2021 Adobe Private Limited, Developed by Sameer.S
</div>
</div>
</body>
</html>
```


## OUTPUT:

### Home Page:

![output](https://github.com/Shaik-sameer-AIML/productcompanywebsite/blob/main/home.JPG?raw=true)
##  products
![output](https://github.com/Shaik-sameer-AIML/productcompanywebsite/blob/main/products.JPG?raw=true)
## people
![output](https://github.com/Shaik-sameer-AIML/productcompanywebsite/blob/main/prople.JPG?raw=true)
## contactus
![output](https://github.com/Shaik-sameer-AIML/productcompanywebsite/blob/main/contact.JPG?raw=true)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
