# Ex.07 Restaurant Website
## Date:16.12.2024

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
home.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - MyMarathi Restaurant</title>
    <style>
   *{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
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
    color: #777;
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
        <h1>AAMCHA MYMARATHICHE SWAGATE!</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <img src="banner.png" alt="Restaurant Banner" class="banner">
        <h2>Pleased to meet you here!</h2>
        <p>Experience the flavours of Maharashtra right from our restaurant!</p>
    </main>
    <footer>
        <p>&copy; 2024 Elfreeda Jesusha J </p>
    </footer>
</body>
</html>

menu.html

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
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
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
    color: #f4a261; /* Light orange on hover */
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
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Our dishes</h2>
        <ul class="menu-list">
            <li><img src="aluvadi.png" alt="Alu vadi">Alu vadi - Rs.40</li>
            <li><img src="thalipeeth.png" alt="Thalipeeth">Thalipeeth - Rs.30</li>
            <li><img src="Kheemyache kanavle.png" alt="Kheemyache kanavle">Kheemyache kanavle - Rs.80</li>
            <li><img src="tallelikolambi.png" alt="Talleli kolambi">Talleli Kolambi - Rs.120</li>
            <li><img src="Muttonrassa.png" alt="Muttonrassa">Mutton Rassa - Rs.200</li>
            <li><img src="kaalamutton.png" alt="kaalamutton">Kaala Mutton - Rs.400</li>
            <li><img src="pavbhaji.png" alt="Pav bhaji">Pav Bhaji - Rs.100</li>
            <li><img src="vadapav.png" alt="Vada pav">Vada pav - Rs.10</li>
            <li><img src="bhainganbharta.png" alt="Bhaingan Bharta">Bhaingan Bharta - Rs.45</li>
            <li><img src="misalpav.png" alt="Misal pav">Misal pav - Rs.30</li>
            <li><img src="Ukadichemodak.png" alt="Ukadiche modak">Ukadiche modak - Rs.20 </li>
            <li><img src="puranpoli.png" alt="Puran poli">Puran poli - Rs.25</li>

        </ul>
    </main>
    <footer>
        <p>&copy; 2024 Elfreeda Jesusha J</p>
    </footer>
</body>
</html>

administration.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - MyMarathi</title>
    <style>
     *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
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
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Our "Family"</h2>
        <div class="team">
            <div class="member">
                <img src="dekhmeraphoto.png" alt="Owner">
                <h3>Elfreeda Jesusha J</h3>
                <p>Owner</p>
            </div>
            <div class="member">
                <img src="kmanager.png" alt="Kitchen Manager">
                <h3>Shailesh Gaikwad<h3>
                <p>Kitchen Manager</p>
            </div>
            <div class="member">
                <img src="fnbmanager.png" alt="Food and Beverage Manager">
                <h3>Sayli Kamble<h3>
                <p>Food and Beverage Manager</p>
            </div>
            <div class="member">
                <img src="gm.png" alt="General Manager">
                <h3>Aryan Joshi<h3>
                <p>General Manager</p>
            </div>
            <div class="member">
                <img src="headchef.png" alt="headchef">
                <h3>Vishal Shinde<h3>
                <p>Head Chef</p>
            </div>
            <div class="member">
                <img src="financier.png" alt="Financier">
                <h3>Madhuri Ingle<h3>
                    <p>Financier</p>
                </div>
            </div>
        </main>
    </body>
    </html>
    
contact.html

<html>
    <title>Contact us</title>
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
    color: #333;
  }
  #contact {
    background-color: #fff;
    padding: 40px 20px;
    margin: 40px auto;
    max-width: 600px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
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
    19/268,Apsara complex,Sector 7,Grant Road,Andheri,Mumbai-400065.
    <br>
    Phone: +91 6455826771
    <br>
    Email: mymarathiofc@gmail.com
    <br>
    Our Branches : Bengaluru  Delhi  Jaipur  Pune  Solapur  Hyderabad  USA  UAE  Canada
  </address>
</section>
</body>
</html>


```


## OUTPUT:

![alt text](<Screenshot 2024-12-16 170554.png>)
![alt text](<Screenshot 2024-12-16 170618.png>)
![alt text](<Screenshot 2024-12-16 170638.png>)
![alt text](<Screenshot 2024-12-16 170638-1.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
