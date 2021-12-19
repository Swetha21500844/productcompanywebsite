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
### HOME PAGE CODE:
 ``` <!DOCTYPE html>
<html lang="en">
  <head>
    <title>WE-CRAFT </title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">WeCraft.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src=![craft](https://user-images.githubusercontent.com/94228215/146681524-48e4794b-0e32-4cad-9c60-d1844417150c.png)
/>
          <div class="contenttext">
            WeCraft, the handmade craft company a wonderful collection of
            handmade items and craft kits. WeCraft is one of the gromming 
            organization that made a remarkable foray in the production of 
            handicraft manufacturing. We manufacture all types of handicraft
            products from everyday use to festive use.
            We stock a range of fun "Do It Yourself" crafting kits.
            Unlike gifts that are mass-produced, you will often find unique 
            differences in each handmade item, which really makes the product and 
            the purchase very special. Nobody in the whole world will have exactly the 
            same item, and that's pretty unique right!
            <br />
            When you buy a handmade gift in WeCraft you know that the makers are so 
            passionate about their craft so each gift is made with love. 
            With handicraft products, there's always a lot of care and affection
            to create something unique and to be treasured 
            <ul>
              <li>So next time you need a gift, a new item for your home, 
                or simply want to treat yourself just consider WeCraft
              </li>
              <li>HAPPY SHOPPING!!!</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 WeCraft, Developed by K.M.Swetha.
      </div>
    </div>
  </body>
</html>
```


PRODUCT PAGE CODE:
```<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WeCraft</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">WeCraft</div>
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
                  <img src="/static/img/pro1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Fabric Wreath</div>
                  <div class="itemprice">Price: Rs.1500.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Gift Tags</div>
                  <div class="itemprice">Price: Rs.300.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/pro3.jpg"  alt="product image">
                </div>
                <div class="itemname">Painting</div>
                <div class="itemprice">Price: Rs.900.00 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/pro4.jpg"  alt="product image">
              </div>
              <div class="itemname">Wall Hangings</div>
              <div class="itemprice">Price: Rs.500.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/pro5.jpg"  alt="product image">
            </div>
            <div class="itemname">Leather craft</div>
            <div class="itemprice">Price: Rs.2500.00 </div>
          </div> <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/pro6.jpg"  alt="product image">
          </div>
          <div class="itemname">Key Chain</div>
          <div class="itemprice">Price: Rs.100.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/pro7.jpg" alt="product image">
            </div>
            <div class="itemname">Name Board</div>
            <div class="itemprice">Price: Rs.3000.00 </div>
        </div><div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/pro8.jpg" alt="product image">
          </div>
          <div class="itemname">Greeting Cards</div>
          <div class="itemprice">Price: Rs.350.00 </div>
      </div><div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/pro9.jpg" alt="product image">
        </div>
        <div class="itemname">Earings</div>
        <div class="itemprice">Price: Rs.250.00 </div>
    </div><div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/pro10.jpg" alt="product image">
      </div>
      <div class="itemname">Candle</div>
      <div class="itemprice">Price: Rs.650.00 </div>
  </div><div class="productitem"> 
    <div class="itemimage">
    <img src="/static/img/pro11.jpg" alt="product image">
    </div>
    <div class="itemname">Soap</div>
    <div class="itemprice">Price: Rs.700.00 </div>
</div><div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/bags.jpg" alt="product image">
  </div>
  <div class="itemname">Bags</div>
  <div class="itemprice">Price: Rs.5000.00 </div>
</div>

          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 WeCraft, Developed by K.M.Swetha.
      </div>
    </div>
  </body>
</html>
```



## OUTPUT:

### Home Page:
![home1 - Copy](https://user-images.githubusercontent.com/94228215/146681677-46c21e05-ce1a-4c82-977f-2dfc9310be8b.png)
![home2](https://user-images.githubusercontent.com/94228215/146681701-a294c5ce-90a5-45c8-a95d-98df3efd451f.png)


### Product Page:
![pr1](https://user-images.githubusercontent.com/94228215/146681777-cdd0ac44-62d1-4fec-912d-c829e6fdec68.png)
![pr2](https://user-images.githubusercontent.com/94228215/146681783-74379523-9337-40d1-90e0-96f28146644a.png)
![pr3](https://user-images.githubusercontent.com/94228215/146681792-cd61c98e-1f9b-4301-be15-c038a3bca326.png)


### People page:
![pp1](https://user-images.githubusercontent.com/94228215/146681819-d3198a99-5481-4db5-90da-75c48d9228b9.png)
![pp3](https://user-images.githubusercontent.com/94228215/146681825-a63d6b2b-5f0f-41da-a4a3-ed0fbffbda44.png)


### Contact us page:
![con1](https://user-images.githubusercontent.com/94228215/146681850-5fd2c22f-50ae-4053-a6ff-c1a9d53ff4d5.png)



## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
