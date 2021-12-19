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
HOME page code:
<!DOCTYPE html>
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
          <img src="./img/banner.jpg" alt="Building" />
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

PRODUCT page code:
<!DOCTYPE html>
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
        <div class="menuitem">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Meet Our Team</h1>
          <table>
            <tr> 
            <td>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/con1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Lisa Su </div> <br>
                  <div class="itemprice"> CEO  </div> 
                </td>
            <td>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/con2.jpg" alt="product image">
                    </div>
                    <div class="itemname"> Karen Lynch </div> <br>
                    <div class="itemprice">Managing Director</div>
                </td>
                <td>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/pp3.jpg" alt="product image">
                        </div>
                        <div class="itemname">Dilip</div> <br>
                        <div class="itemprice">Project Director</div>

                </td>  
            </tr>
            <tr>
                <td>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/pp4.jpg" alt="product image">
                        </div>
                        <div class="itemname">Barry Leo</div> <br>
                        <div class="itemprice">Senior Manager</div>
                    </td>
                    <td>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="/static/img/pp5.jpg" alt="product image">
                            </div>
                            <div class="itemname">Safra Catz</div><br>
                            <div class="itemprice"> Manager</div>

                    </td>
                    <td>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="/static/img/pp6.jpg" alt="product image">
                            </div>
                            <div class="itemname">David Hason</div> <br>
                            <div class="itemprice">Senior Team Leader</div>
                    </td>

            </tr>    
            </table>
            </div>
            </div>
        </body>
        </html>
PEOPLE page code:
  <!DOCTYPE html>
<html lang="en">
  <head>
    <title>WeCraft</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
     
        <div class="menuitem">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content"><!DOCTYPE html>
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
                <div class="menuitem">
                  <a href="/static/products.html">Products</a>
                </div>
                <div class="menuitemselected"><a href="/static/people.html">People</a></div>
                <div class="menuitem"><a>Contact Us</a></div>
              </div>
              <div class="content">
                <div class="productcontent">    
                  <h1>Meet Our Team</h1>
                  <table>
                    <tr> 
                    <td>
                      <div class="productitem"> 
                          <div class="itemimage">
                          <img src="/static/img/con1.jpg" alt="product image">
                          </div>
                          <div class="itemname">Lisa Su </div> <br>
                          <div class="itemprice"> CEO  </div> 
                        </td>
                    <td>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="/static/img/con2.jpg" alt="product image">
                            </div>
                            <div class="itemname"> Karen Lynch </div> <br>
                            <div class="itemprice">Managing Director</div>
                        </td>
                        <td>
                            <div class="productitem"> 
                                <div class="itemimage">
                                <img src="/static/img/pp3.jpg" alt="product image">
                                </div>
                                <div class="itemname">Dilip</div> <br>
                                <div class="itemprice">Project Director</div>
        
                        </td>  
                    </tr>
                    <tr>
                        <td>
                            <div class="productitem"> 
                                <div class="itemimage">
                                <img src="/static/img/pp4.jpg" alt="product image">
                                </div>
                                <div class="itemname">Barry Leo</div> <br>
                                <div class="itemprice">Senior Manager</div>
                            </td>
                            <td>
                                <div class="productitem"> 
                                    <div class="itemimage">
                                    <img src="/static/img/pp5.jpg" alt="product image">
                                    </div>
                                    <div class="itemname">Safra Catz</div><br>
                                    <div class="itemprice"> Manager</div>
        
                            </td>
                            <td>
                                <div class="productitem"> 
                                    <div class="itemimage">
                                    <img src="/static/img/pp6.jpg" alt="product image">
                                    </div>
                                    <div class="itemname">David Hason</div> <br>
                                    <div class="itemprice">Senior Team Leader</div>
                            </td>
        
                    </tr>    
                    </table>
                    </div>
                    </div>
                </body>
                </html>
        

            </tr>    
            </table>
            </div>
            </div>
        </body>
        </html>
CONTACT page code:
<!DOCTYPE html>
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
        <div class="menuitem">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="contactus" background-image="url(/static/img/cbg.jpg")>
          OFFICE ADDRESS <br>
          <hr style="height:2px;border-width:5px;color:#e6752f;background-color: #e6752f">
          
          806v, 
          Marque Estate,<br>
          Chennai,<br>
          76009,<br>
          India<br>

          CONTACT ADDRESS<br>
          <hr style="height:2px;border-width:5px;color:#e6752f;background-color: #e6752f">
          
          Tel: 044-87635421
               044-87635422
          Fax: 0091-67-6784890
          E-mail: Wcrft4528@manufav.com
          <br>
           For Service Queries or Complaints: sales.wc@Service.com
        
        </div>
        <div class="footer">
            Copyright &#169; 2021 WeCraft, Developed by K.M.SWETHA.
          </div>

      </div>
      </body>
      </html>
   
  
  


## OUTPUT:

### Home Page:

![output](./images/homepage.jpg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
