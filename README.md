# Ex.07 Software Product Company Website
## Date:1/1/23

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
<html lang="en">
  <head>
    <title>Royalreader Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>ROYALREADER PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html"><b>Home</b></a></div>
        <div class="menuitem"><a href="/static/products.html"><b>Products</b></a></div>
        <div class="menuitem"><a href="/static/people.html"><b>People</b></a></div>
        <div class="menuitem"><a href="/static/contact.html"><b>Contact Us</b></a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/books.jpg" alt="Building" />
          <div class="contenttext">
            India has been pioneering quality publishing for teachers and institutions. The passion to transform lives is at the centre of our ideology. Royalreader textbooks, developed by leading academicians and practicing teachers are research-based, learner-centric and are the first choice of over 15,000 institutes pan India. Our resources lead the teaching-learning through new methodologies, and sound teaching practices that inspire learners to achieve more through engaging digital and print content.
            <br>
            <br>
            pringer Nature Group, a global and progressive business that opens doors to discovery. Our 500 passionate team members are spread over 26 offices in India. Over 15 million learners use our learning resources, which include 200 new titles every year. Over 50,000 teachers receive professional development inputs from us.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2022 Royalreader Private Limited, Developed by Surendhar K.
      </div>
    </div>
  </body>
</html>
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Royalreader Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>ROYALREADER PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html"><b>Home</b></a></div>
        <div class="menuitemselected">
          <a href="/static/products.html"><b>Products</b></a>
        </div>
        <div class="menuitem"><a href="/static/people.html"><b>People</b></a></div>
        <div class="menuitem"><a href="/static/contact.html"><b>Contact Us</b></a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/bennett.jpg" alt="product image">
                  </div>
                  <div class="itemname">The Vanishing Half</div>
                  <div class="itemprice">Price: Rs.4799.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/divergent.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Divergent</div>
                  <div class="itemprice">Price: Rs.5299.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/code.jpg"  alt="product image">
                  </div>
                  <div class="itemname">The da vinci code</div>
                  <div class="itemprice">Price: Rs.5000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/gaiman.jpg"  alt="product image">
                  </div>
                  <div class="itemname">American Gods</div>
                  <div class="itemprice">Price: Rs.5899.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/hater.jpg"  alt="product image">
                  </div>
                  <div class="itemname">The Hate You Give</div>
                  <div class="itemprice">Price: Rs.6299.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/hoover.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Verity</div>
                  <div class="itemprice">Price: Rs.5699.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/kazuo.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Klara and the Sun</div>
                  <div class="itemprice">Price: Rs.5199.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/mexican.jpg"  alt="product image">
                  </a>
                  </div>
                  <div class="itemname">Mexican Gothic</div>
                  <div class="itemprice">Price: Rs.5499.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/ocean.jpg"  alt="product image">
                  </div>
                  <div class="itemname">On Earth We're Briefly Gorgeous</div>
                  <div class="itemprice">Price: Rs.6399.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/roses.jpg"  alt="product image">
                  </div>
                  <div class="itemname">A Court Of Thorns And Roses</div>
                  <div class="itemprice">Price: Rs.7199.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/seven.jpg"  alt="product image">
                  </div>
                  <div class="itemname">The Seven Husbands Of Evenly Hugo</div>
                  <div class="itemprice">Price: Rs.7499.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/stephen.jpg"  alt="product image">
                  </div>
                  <div class="itemname">The Shining</div>
                  <div class="itemprice">Price: Rs.6999.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/Six-of-Crows.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Six Of Crows</div>
                  <div class="itemprice">Price: Rs.7999.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/turtles.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Turtles All The Way Down</div>
                  <div class="itemprice">Price: Rs.7499.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/whitehead.jpg"  alt="product image">
                  </div>
                  <div class="itemname">The Underground Railground</div>
                  <div class="itemprice">Price: Rs.7799.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2022 Royalreader Private Limited, Developed by Surendhar K.
      </div>
    </div>
  </body>
</html>
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Royalreader Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>ROYALREADER PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html"><b>Home</b></a></div>
        <div class="menuitem"><a href="/static/products.html"><b>Products</b></a></div>
        <div class="menuitemselected"><a href="/static/people.html"><b>People</b></a></div>
        <div class="menuitem"><a href="/static/contact.html"><b>Contact Us</b></a></div>
      </div>
      <body>
          <div class="content">
              <h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Our Proud Management Crew!!!</h2>
              <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/chairman.jpeg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Lee Yung (Chairman)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/head1.jpeg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  John Nickson (Head Executive)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/head2.jpeg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Albert Rio (Head Executive)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/manager1.jpeg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Maddy Nelson (Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/manager2.jpeg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Remi Juliet (Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/deputy.jpeg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Max Mysterio (Deputy Manager)</h2></centre>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Royalreader Private Limited, Developed by Surendhar K.
      </div>
    </div>
  </body>
</html>
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Royalreader Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>ROYALREADER PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html"><b>Home</b></a></div>
        <div class="menuitem"><a href="/static/products.html"><b>Products</b></a></div>
        <div class="menuitem"><a href="/static/people.html"><b>People</b></a></div>
        <div class="menuitemselected"><a href="/static/contact.html"><b>Contact Us</b></a></div>
      </div>
      <body>
          <div class="content">
          <h1>&ensp;Contact Information</h1>
                    <p><b>&emsp;Here are the details listed below. Do contact us for any need</b></p>
                    <p><b>&emsp;&ensp;Address:</b>
                         No:98, king street, Flyer Town, Texas, United States
                    </p>
                    <ul>
                        <br>
                        <li><b>&emsp;Phone:</b>&emsp;2387459648</li>
                        <br>
                        <li><b>&emsp;Shop owner no</b>:&emsp;9586456745</li>
                        <br>
                        <li><b>&emsp;Shop Manager Number:</b> 8975455185</li>
                        <br>
                        <li><b>&emsp;Email Id:</b>&emsp;royalreader74@gmail.com</li>
                        <br>
                        <li><b>&emsp;Alternate Email Id:</b>&emsp;royalreader89@gmail.com</li>
                        <br>
                    </ul>
                </div>
          </div>
          </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Royalreader Private Limited, Developed by Surendhar K.
      </div>
    </div>
  </body>
</html>

```
## OUTPUT:
![image](https://github.com/moulidharyadav/softweb/assets/147078316/398173a6-727b-4944-a80f-b2940ceb1db4)
![image](https://github.com/moulidharyadav/softweb/assets/147078316/84a63aa2-781d-4c77-a466-22f3ef66ecb1)
![image](https://github.com/moulidharyadav/softweb/assets/147078316/3c97c072-f62c-4e36-b590-a2bd35fbc68b)
![image](https://github.com/moulidharyadav/softweb/assets/147078316/05ae047f-f648-4509-b663-4283b512e187)
![image](https://github.com/moulidharyadav/softweb/assets/147078316/c3aa8f5b-6b0f-4693-a855-0d65c095e7bc)
![image](https://github.com/moulidharyadav/softweb/assets/147078316/45a592d1-b696-4570-b85b-210d6899316b)
![image](https://github.com/moulidharyadav/softweb/assets/147078316/d73c85dc-e3cf-4ee3-acca-c3a669c9980a)
![image](https://github.com/moulidharyadav/softweb/assets/147078316/5ea81319-04f5-4a3e-82ce-d7574321addb)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
