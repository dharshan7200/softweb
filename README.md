# Ex.07 Software Product Company Website
## AIM:
To develop a static company website to display the softwares and services provided by the company.

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

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
{% load static %}
<html lang="en">
  <head>
    <title>Aj-Private Limited</title>
    <link rel="stylesheet" href="static/css/layout.css" />
    <link rel="icon" href="static/images/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AJ-Private Limited</div>
      <div class="menu">
        <div class="menuitemselected"><a href="company.html">Home</a></div>
        <div class="menuitem"><a href="product.html">Products</a></div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="static/images/iron.png" style="width:300px; height:300px;" />
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
                Copyright &#169; 2022 YUHAMA-Private.LTD, Developed by YUVARAJ

      </div>
    </div>
  </body>
</html>

<!DOCTYPE html>
{% load static %}
<html lang="en">
  <head>
    <title>Aj-Private Limited</title>
    <link rel="stylesheet" href="static/css/layout.css" />
    <link rel="icon" href="static/images/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AJ-Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="company.html">Home</a></div>
        <div class="menuitemselected">
          <a href="product.html">Products</a>
        </div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
    </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img1.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Simple Steps</div>
                  <div class="itemprice">Price: Rs.12,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img2.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Author edision </div>
                  <div class="itemprice">Price: Rs.14,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img3.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally GST</div>
                  <div class="itemprice">Price: Rs.15,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img4.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally PRIME</div>
                  <div class="itemprice">Price: Rs.18,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img5.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Essential</div>
                  <div class="itemprice">Price: Rs.11,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img6.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Power of simplcity </div>
                  <div class="itemprice">Price: Rs.13,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img7.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Impleating</div>
                  <div class="itemprice">Price: Rs.14,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img8.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Advance</div>
                  <div class="itemprice">Price: Rs.20,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img9.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally GST 4th edision</div>
                  <div class="itemprice">Price: Rs.19,000.00 </div>
              </div>

              
            
              
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2022 YUHAMA-Private.LTD, Developed by YUVARAJ
      </div>
    </div>
  </body>
</html>
<!DOCTYPE html>
{% load static %}
<html lang="en">
  <head>
    <title>Aj-Private Limited</title>
    <link rel="stylesheet" href="static/css/layout.css" />
    <link rel="icon" href="static/images/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AJ-Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="company.html">Home</a></div>
        <div class="menuitemselected">
          <a href="product.html">Products</a>
        </div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
    </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img1.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Simple Steps</div>
                  <div class="itemprice">Price: Rs.12,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img2.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Author edision </div>
                  <div class="itemprice">Price: Rs.14,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img3.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally GST</div>
                  <div class="itemprice">Price: Rs.15,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img4.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally PRIME</div>
                  <div class="itemprice">Price: Rs.18,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img5.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Essential</div>
                  <div class="itemprice">Price: Rs.11,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img6.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Power of simplcity </div>
                  <div class="itemprice">Price: Rs.13,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img7.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Impleating</div>
                  <div class="itemprice">Price: Rs.14,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img8.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Advance</div>
                  <div class="itemprice">Price: Rs.20,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img9.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally GST 4th edision</div>
                  <div class="itemprice">Price: Rs.19,000.00 </div>
              </div>

              
            
              
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2022 YUHAMA-Private.LTD, Developed by YUVARAJ
      </div>
    </div>
  </body>
</html>
<!DOCTYPE html>
{% load static %}
<html lang="en">
  <head>
    <title>Aj-Private Limited</title>
    <link rel="stylesheet" href="static/css/layout.css" />
    <link rel="icon" href="static/images/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AJ-Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="company.html">Home</a></div>
         <div class="menuitem">
          <a href="product.html">Products</a></div>
        <div class="menuitemselected"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
        
        <div class="content">
        <div class="productcontent">    
          <h1>People Of Company </h1>
          <figure>

        
        <p>
            <img src="static/images/img2/pre.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>PRESIDENT</h2></figcaption>
        <hr>
        
      
        <p>
            <img src="static/images/img2/fou.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>FOUNDER</h2></figcaption>
        <hr>
        
        
       <p>
            <img src="static/images/img2/mang.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>CO-FOUNDER</h2></figcaption>
        <hr>
        
        
        <p>
            <img src="static/images/img2/head.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>DIRECTOR</h2></figcaption>
        <hr>
        
        
        <p>
            <img src="static/images/img2/vk.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>MANAGER</h2></figcaption>
        <hr>

        <p>
            <img src="static/images/img2/aj.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>HEAD</h2></figcaption>
        <hr>
       </figure>
          </div>
      </div>
       <div class="footer">
       Copyright &#169; 2022 YUHAMA-Private.LTD, Developed by YUVARAJ
     </div>
    </div>
    
    
    
  </body>
 
</html>
```
## OUTPUT:
![image](https://github.com/dharshan7200/softweb/assets/138850116/b9fb8257-9290-4011-9eb0-4d61b34e72df)

![image](https://github.com/dharshan7200/softweb/assets/138850116/919d20f6-535e-452d-a932-62a80700232b)

![image](https://github.com/dharshan7200/softweb/assets/138850116/583edc1e-9ce7-4f2b-a047-e680e52847f4)

![image](https://github.com/dharshan7200/softweb/assets/138850116/004fdb32-a4b4-4307-aa6b-28041c4067f2)


## HTML VALIDATOR:


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
