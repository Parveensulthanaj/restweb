# Ex.07 Restaurant Website
## Date:12:12:2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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
<home1 class="html">
    <html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - My Restaurant</title>
    <style>
   *{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

body {
    font-family: Arial, sans-serif;
    background-color: #49ad30;
    color: #b31c1c;
}

header {
    background-color: #d61a1a;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #a0bc13;
    text-decoration: none;
    font-size: 1.2rem;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #f4a261; 
}

main {
    text-align: center;
    padding: 40px 20px;
}

.banner {
    width: 100%;
    height: auto;
    max-height: 400px; 
    object-fit: cover; 
    margin-bottom: 30px;
}

h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #333;
}

p {
    font-size: 1.2rem;
    color: #661bc8;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
</style>
</head>
<body>
    <header>
        <h1>Welcome to My Restaurant</h1>
        <nav>
            <ul>
                <li><a href="home1.html">Home</a></li>
                <li><a href="menu1.html">Menu</a></li>
                <li><a href="administration1.html">Administration</a></li>
                <li><a href="contact1.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <img src="b2.png" alt="Restaurant Banner" class="banner">
        <h2>EAT AND MEAT!</h2>
        <p>IF YOU NEVER THE FOOD YOU NEVER KNOWS THE TASTE.</p>
    </main>
    <footer>
        <p>&copy; 2024 Parveen Sulthana</p>
    </footer>
</body>
</html>
</home1>



<menu1 class="html">
    <html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - My Restaurant</title>
   <style>
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
     }

body {
    font-family: Arial, sans-serif;
    background-color: #ee2020;
    color: #19b8e9;
}

header {
    background-color: #0bd5a6;
    color: #2d12b3;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2rem;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #f4a261; /* Light orange on hover */
}

main {
    padding: 40px 20px;
    text-align: center;
}

h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #1981cb7a;
}

.menu-list {
    list-style-type: none;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 20px;
    justify-items: center;
}

.menu-list li {
    background-color: #fff;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 100%;
    text-align: center;
}

.menu-list img {
    width: 100%;
    height: auto;
    border-radius: 5px;
    margin-bottom: 15px;
}

.menu-list li p {
    font-size: 1.1rem;
    color: #333;
    font-weight: bold;
}

.menu-list li:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}


footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
</style>
</head>
<body>
    <header>
        <h1>Our Menu</h1>
        <nav>
            <ul>
                <li><a href="home1.html">Home</a></li>
                <li><a href="menu1.html">Menu</a></li>
                <li><a href="administration1.html">Administration</a></li>
                <li><a href="contact1.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Food Items</h2>
        <ul class="menu-list">
            <li><img src="C:\Users\mouli\OneDrive\Pictures\Screenshots\veg.png" alt="Food Item 1">CHETTINAD SAMAYAL - $10<p><i>IT IS A DELICIOUS FOOD MOSTLY PREFERRED AS LUNCH IN SOUTH INDIA.</i></p></li>
            <li><img src="veg1.png" alt="Food Item 2">GIANT VARIETY RICE - $8<p><i>VARIETY RICE GIVES UNIQUE TASTE IN OTHER OTHER,MOSTLY FAMOUS IN ALL OVER INDIA</i></p></li>
            <li><img src="veg2.png" alt="Food Item 3">WESTERN SUSHI - $12<p><i>GRILLED SUSHI GIVES A VERY SPICY TASTE</i></p></li>
            <li><img src="veg3.png" alt="Food Item 4">TANDOORI - $7<p><i>TANDOORI CHICKEN IS A GIANT CHICKEN WHICH TASTES AWESOME LEVEL EXPERIENCE</i></p></li>
            <li><img src="veg4.png" alt="Food Item 5">CHICKEN FRIES - $15<p><i>CHICKEN FRIES CONTAINS SPICY MASALA WITH SAUS AND MYONISSE</i></p></li>
            <li><img src="veg5.png" alt="Food Item 6">VEG CUTLETS - $5<p><i>MOSTLY VEG CUTSLETS ARE GOOD AND MAINTAIN THE HEALTY DIET , WITH SPICY AND LITE SWEETY</i></p></li>
            <li><img src="veg6.png" alt="Food Item 7">CHICKEN GRAY - $6<p><i>CHICKEN GRAVY TASTES GOOD AND HAVE A PERFECT COMBINATION WITH PARROTA</i></p></li>
            <li><img src="veg7.png" alt="Food Item 8">MUTTON CUTLET - $4<p><i>MUTTON CUTLETS ARE GOOD SNACKS RECIPES AVAILALBLE IN OUR RESTARURANT</i></p></li>
            <li><img src="veg8.png" alt="Food Item 9">ANDHRA CHETTINAD - $5<p><i>ANDHRA LUNCH ARE MOSTLYSPICY IN NATURE</i></p></li>
            <li><img src="veg9.png" alt="Food Item 10">HYDERBAD KAANA - $6<p><i>IT IS A FAMOUS DISH, OBTAINED FROM BAASMATI RICE</i></p></li>
            <li><img src="veg13.png" alt="Food Item 11">NOODLES - $6<p>NOODLES ARE MOSTLY FAMOUS IN CHINA</p></li>
            <li><img src="veg11.png" alt="Food Item 12">KERALA GIANT KAANA  - $6<p><i>IT IS FAMOUS DUE TO BOAT RIDE  KAANA KERLA</i></p></li>

        </ul>
    </main>
    <footer>
        <p>&copy; 2024 Parveen Sulthana</p>
    </footer>
</body>
</html>
</menu1>


<administration class="html">
    <html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - My Restaurant</title>
    <style>
     *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #14b9b6;
}

header {
    background-color: #1acfb0c9;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2rem;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #f4a261; 
}

main {
    padding: 40px 20px;
    text-align: center;
}

h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #333;
}


.team {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 30px;
    justify-items: center;
    margin-top: 30px;
}

.member {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.member img {
    width: 100%;
    height: auto;
    border-radius: 50%;
    margin-bottom: 15px;
    border: 4px solid #f4a261; 
}

.member h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
    color: #333;
}

.member p {
    font-size: 1.1rem;
    color: #777;
}

.member:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}

h3 {
    margin-bottom: 10px;
    font-size: 1.5rem;
    color: #333;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
</style>
</head>
<body>
    <header>
        <h1>Administration Team</h1>
        <nav>
            <ul>
                <li><a href="home1.html">Home</a></li>
                <li><a href="menu1.html">Menu</a></li>
                <li><a href="administration1.html">Administration</a></li>
                <li><a href="contact1.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Meet Our Team</h2>
        <div class="team">
            <div class="member">
                <img src="mypic.png" alt="Member 1">
                <h3>Parveen Sulthana</h3>
                <p>CEO</p>
            </div>
            <div class="member">
                <img src="sel.png" alt="Member 2">
                <h3>Selshiys Francis<h3>
                <p>Marketing Manager</p>
            </div>
            <div class="member">
                <img src="reb.png" alt="Member 3">
                <h3>Paul Amala Infantia<h3>
                <p>Operations Manager</p>
            </div>
            <div class="member">
                <img src="paul.png" alt="Member 4">
                <h3>Rebecca<h3>
                <p>HR Manager</p>
            </div>
            <div class="member">
                <img src="joyal cris.png" alt="Member 5">
                <h3>Joyal Cris<h3>
                <p>Executive Chef</p>
            </div>
            <div class="member">
                <img src="thomas.png" alt="Member 6">
                <h3>Joseph<h3>
                <p>Customer Service Manger</p>
            </div>
        </div>
    </main>
<footer>
        <p>&copy; 2024 Parveen Sulthana</p>
    </footer>
</body>
</html>
</administration>

<contact class="html">
    <body>
        <style>
        *{
          margin: 0;
          padding: 0;
          box-sizing: border-box;
        }
      
      body {
        font-family: Arial, sans-serif;
        background-color: #f4f4f4;
        color: #333333;
      }
      #contact {
        background-color: #98c91b;
        padding: 40px 20px;
        margin: 40px auto;
        max-width: 600px;
        border-radius: 8px;
        box-shadow: 0 4px 8px rgba(178, 16, 16, 0.1);
        text-align: center;
      }
      
      #contact h2 {
        font-size: 2rem;
        margin-bottom: 20px;
        color: #333;
      }
      
      #contact p {
        font-size: 1.2rem;
        margin-bottom: 20px;
        color: #555;
      }
      
      address {
        font-size: 1.1rem;
        line-height: 1.6;
        color: #333;
      }
      
      address br {
        margin-bottom: 10px;
      }
      
      #contact:hover {
        transform: translateY(-5px);
        box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
      }
        </style>
         <section id="contact">
        <h2>Contact Us</h2>
        <p>Visit us at:</p>
        <address>
          16A,sathyamoorthy road,sharab bazaar backside,Tiruvannamalai.
          <br>
          Phone: 9342189324
          <br>
          Email: noorij750@gmail.com.com
        </address>
      </section>
      </body>
      </html>      
</contact>


```

## OUTPUT:

![alt text](homehost.png)
![alt text](menuhost.png)
![alt text](adminhost.png)
![alt text](contacthost.png)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
