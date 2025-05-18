## Ex.07 Restaurant Website
## Date:18-05-2025

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
~~~
rest.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration</title>

    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            background-color: #00d0f0;
            box-sizing: border-box;
        }
        
        *,
        *::before,
        *::after {
            box-sizing: inherit;
        }
        
        header {
            background: #27cbbe;
            color: rgb(69, 171, 199);
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(1, 33, 15, 0.1);
        }
        
        header h1 {
            font-size: 1.8rem;
            font-family: 'Playfair Display', serif;
        }
        
        header nav a {
            text-decoration: none;
            color: rgb(33, 121, 176);
            font-weight: 500;
            margin: 0 15px;
            transition: color 0.3s ease;
            font-size: 1rem;
        }
        
        header nav a:hover {
            color: #2a688b;
        }
        
        .admin-container {
            padding: 40px 20px;
            background: #743793;
            text-align: center;
        }
        
        .admin-container h1 {
            font-size: 2.5rem;
            color: #000000;
            margin-bottom: 20px;
            font-family: 'Playfair Display', serif;
        }
        
        .admin-items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }
        
        .admin-item {
            background: rgb(177, 198, 54);
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 280px;
            overflow: hidden;
            transition: transform 0.3s ease;
            text-align: left;
        }
        
        .admin-item img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }
        
        .admin-item:hover {
            transform: scale(1.05);
        }
        
        .admin-details {
            padding: 15px;
        }
        
        .admin-details h3 {
            font-size: 1.4rem;
            color: #2c3e50;
            margin-bottom: 8px;
        }
        
        .admin-details p {
            font-size: 1rem;
            color: #555;
            margin-bottom: 10px;
        }
        
        footer {
            background: #978b5a;
            color: rgb(123, 154, 169);
            text-align: center;
            padding: 15px 0;
        }
        
        footer a {
            color: #dba419;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }
        
        footer a:hover {
            color: #ecf0f1;
        }
        
        @media (max-width: 768px) {
            header h1 {
                font-size: 1.5rem;
            }
            .admin-items {
                flex-direction: column;
                gap: 20px;
            }
            .admin-item {
                width: 100%;
            }
            header nav a {
                font-size: 0.9rem;
                margin: 0 5px;
            }
        }
    </style>
</head>

<body>
    <div class="admin-container">
        <h1>OUR ADMINISTATORS</h1>
        <div class="admin-items">
            <div class="admin-item">
                <img src="CHEF 2.jpg" CEO ">
                <div class="admin-details ">
                    <h3>DAMU</h3>
                    <p>CEO of THE WAVE RESTAURENT</p>
                </div>
            </div>

            <div class="admin-item ">
                <img src="CHEF 1.jpg "Manager">
                <div class="admin-details">
                    <h3>SARAVANAN</h3>
                    <p>Manager of THE WAVE RESTAURENT</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="CHE.jpg" Master Chef ">
                <div class="admin-details ">
                    <h3>VENKATESH BHATT</h3>
                    <p>Master Chef of THE WAVE RESTAURENT</p>
                </div>
            </div>

            <div class="admin-item ">
                <img src="sunitha.jpg "Assistant Managing Director">
                <div class="admin-details">
                    <h3>SUNITHA</h3>
                    <p>Assistant Managing Director of THE WAVE RESTAURENT</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <a href="rest.html">Back to Home</a></p>
    </footer>
    <H3 ALIGN="CENTER">DESIGNED AND DEVELOPED BY K.MANOJKUMAR</H3>
</body>
</html>

menu.html

<html>
<title>Menu</title>

<head>
    <style>
        .main {
            width: 98%;
            height: 98%;
            background-color: bisque;
            justify-content: center;
            border: 2px solid black;
            border-radius: 20px;
        }
        
        .main h1 {
            width: 500px;
            position: relative;
            top: 1px;
            left: 480px;
            border: 1px;
            border-radius: 100px;
            padding: 5px;
            background-color: black;
            color: rgb(230, 234, 238);
            font-family: 'Times New Roman', Times, serif;
            font-size: 50px;
        }
        
        .h1 {
            display: flex;
            justify-content: space-around;
            position: relative;
            left: 35px;
            width: 95%;
            height: 90%;
        }
        
        .h2 {
            display: flex;
            justify-content: space-around;
            position: relative;
            left: 35px;
            bottom: 400px;
            width: 95%;
            height: 90%;
        }
        
        .i1 {
            width: 20%;
            height: 40%;
            color: rgb(217, 223, 230, 217);
            background-image: url("fried\ chicken.jpg");
            background-size: cover;
            background-color: darkblue;
            border: 1px solid darkblue;
            border-radius: 50px;
        }
        
        .i2 {
            width: 20%;
            height: 40%;
            color: rgb(217, 223, 230, 217);
            background-image: url("french\ fries.jpg");
            background-size: cover;
            background-color: darkblue;
            border: 1px solid darkblue;
            border-radius: 50px;
        }
        
        .i3 {
            width: 20%;
            height: 40%;
            color: rgb(217, 223, 230, 217);
            background-image: url("PIZZA.jpeg");
            background-size: cover;
            background-color: darkblue;
            border: 1px solid darkblue;
            border-radius: 50px;
        }
        
        .i4 {
            width: 20%;
            height: 40%;
            color: rgb(217, 223, 230, 217);
            background-image: url("PANCAKE.jpeg");
            background-size: cover;
            background-color: darkblue;
            border: 1px solid darkblue;
            border-radius: 50px;
        }
        
        .i5 {
            width: 20%;
            height: 40%;
            color: rgb(217, 223, 230, 217);
            background-image: url("burger.jpeg");
            background-size: cover;
            background-color: darkblue;
            border: 1px solid darkblue;
            border-radius: 50px;
        }
        
        .i6 {
            width: 20%;
            height: 40%;
            color: rgb(217, 223, 230, 217);
            background-image: url("CAKE.jpg");
            background-size: cover;
            background-color: darkblue;
            border: 1px solid darkblue;
            border-radius: 50px;
        }
        
        .i7 {
            width: 20%;
            height: 40%;
            color: rgb(217, 223, 230, 217);
            background-image: url("pasta.jpg");
            background-size: cover;
            background-color: darkblue;
            border: 1px solid darkblue;
            border-radius: 50px;
        }
        
        .i8 {
            width: 20%;
            height: 40%;
            color: rgb(217, 223, 230, 217);
            background-image: url("parrota.jpg");
            background-size: cover;
            background-color: darkblue;
            border: 1px solid darkblue;
            border-radius: 50px;
        }
        
        .i9 {
            width: 20%;
            height: 40%;
            color: rgb(217, 223, 230, 217);
            background-image: url("kulfi.jpeg");
            background-size: cover;
            background-color: darkblue;
            border: 1px solid darkblue;
            border-radius: 50px;
        }
        
        .i10 {
            width: 20%;
            height: 40%;
            color: rgb(217, 223, 230, 217);
            background-image: url("idly.jpg");
            background-size: cover;
            background-color: darkblue;
            border: 1px solid darkblue;
            border-radius: 50px;
        }
        
        .i11 {
            width: 20%;
            height: 40%;
            color: rgb(217, 223, 230, 217);
            background-image: url("BIRIYANI.jpeg");
            background-size: cover;
            background-color: darkblue;
            border: 1px solid darkblue;
            border-radius: 50px;
        }
        
        .i12 {
            width: 20%;
            height: 40%;
            color: rgb(217, 223, 230, 217);
            background-image: url("SAND.jpeg");
            background-size: cover;
            background-color: darkblue;
            border: 1px solid darkblue;
            border-radius: 50px;
        }
        
        h2 {
            color: aliceblue;
            position: relative;
            left: 30px;
            border: 1px solid rgb(12, 12, 20);
            background-color: rgb(10, 10, 13);
            width: 80%;
            height: 8%;
            border-radius: 80px;
        }
    </style>
</head>

<body>
    <div class="main">
        <h1 align="center">MENU CARD</h1>

        <div class="h1">
            <div class="i1">
                <h2 align="center">LOLLIPOP</h2>

            </div>
            <div class="i2">
                <h2 align="center">FRIES</h2>

            </div>
            <div class="i3">
                <h2 align="center">PIZZA</h2>

            </div>
            <div class="i4">
                <h2 align="center">PANCAKE</h2>

            </div>
            <div class="i5">
                <h2 align="center">BURGER</h2>

            </div>
            <div class="i6">
                <h2 align="center">CAKE</h2>

            </div>
        </div>
        <div class="h2">
            <div class="i7">
                <h2 align="center">PASTA</h2>

            </div>
            <div class="i8">
                <h2 align="center">PARROTA</h2>

            </div>
            <div class="i9">
                <h2 align="center">KULFI</h2>

            </div>
            <div class="i10">
                <h2 align="center">IDLI</h2>

            </div>
            <div class="i11">
                <h2 align="center">BIRIYANI</h2>

            </div>
            <div class="i12">
                <h2 align="center">SANDWITCH</h2>

            </div>
        </div>

    </div>
</body>
</html>

admin.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration</title>

    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            background-color: #00d0f0;
            box-sizing: border-box;
        }
        
        *,
        *::before,
        *::after {
            box-sizing: inherit;
        }
        
        header {
            background: #27cbbe;
            color: rgb(69, 171, 199);
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(1, 33, 15, 0.1);
        }
        
        header h1 {
            font-size: 1.8rem;
            font-family: 'Playfair Display', serif;
        }
        
        header nav a {
            text-decoration: none;
            color: rgb(33, 121, 176);
            font-weight: 500;
            margin: 0 15px;
            transition: color 0.3s ease;
            font-size: 1rem;
        }
        
        header nav a:hover {
            color: #2a688b;
        }
        
        .admin-container {
            padding: 40px 20px;
            background: #743793;
            text-align: center;
        }
        
        .admin-container h1 {
            font-size: 2.5rem;
            color: #000000;
            margin-bottom: 20px;
            font-family: 'Playfair Display', serif;
        }
        
        .admin-items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }
        
        .admin-item {
            background: rgb(177, 198, 54);
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 280px;
            overflow: hidden;
            transition: transform 0.3s ease;
            text-align: left;
        }
        
        .admin-item img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }
        
        .admin-item:hover {
            transform: scale(1.05);
        }
        
        .admin-details {
            padding: 15px;
        }
        
        .admin-details h3 {
            font-size: 1.4rem;
            color: #2c3e50;
            margin-bottom: 8px;
        }
        
        .admin-details p {
            font-size: 1rem;
            color: #555;
            margin-bottom: 10px;
        }
        
        footer {
            background: #978b5a;
            color: rgb(123, 154, 169);
            text-align: center;
            padding: 15px 0;
        }
        
        footer a {
            color: #dba419;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }
        
        footer a:hover {
            color: #ecf0f1;
        }
        
        @media (max-width: 768px) {
            header h1 {
                font-size: 1.5rem;
            }
            .admin-items {
                flex-direction: column;
                gap: 20px;
            }
            .admin-item {
                width: 100%;
            }
            header nav a {
                font-size: 0.9rem;
                margin: 0 5px;
            }
        }
    </style>
</head>

<body>
    <div class="admin-container">
        <h1>OUR ADMINISTATORS</h1>
        <div class="admin-items">
            <div class="admin-item">
                <img src="CHEF 2.jpg" CEO ">
                <div class="admin-details ">
                    <h3>DAMU</h3>
                    <p>CEO of THE WAVE RESTAURENT</p>
                </div>
            </div>

            <div class="admin-item ">
                <img src="CHEF 1.jpg "Manager">
                <div class="admin-details">
                    <h3>SARAVANAN</h3>
                    <p>Manager of THE WAVE RESTAURENT</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="CHE.jpg" Master Chef ">
                <div class="admin-details ">
                    <h3>VENKATESH BHATT</h3>
                    <p>Master Chef of THE WAVE RESTAURENT</p>
                </div>
            </div>

            <div class="admin-item ">
                <img src="sunitha.jpg "Assistant Managing Director">
                <div class="admin-details">
                    <h3>SUNITHA</h3>
                    <p>Assistant Managing Director of THE WAVE RESTAURENT</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <a href="rest.html">Back to Home</a></p>
    </footer>
    <H3 ALIGN="CENTER">DESIGNED AND DEVELOPED BY K.MANOJKUMAR</H3>
</body>
</html>

contact.html

<html>

<head>
    <title> CONTACT </title>
    <style>
        body {
            background-size: cover;
            background-position: center;
        }
        
        body {
            display: inline blocks;
            margin: 0 600px;
            font-family: MS Sans Serif;
            text-decoration: royalblue;
            font-size: 30px;
            font-weight: bolder;
            background-image: url("bg3.jpg");
            position: absolute;
            top: 200px;
        }
    </style>
</head>

<body>
    <div class="nav-list">
    </div>
    <center>
        <section id="contact">
            <h1 style="color:rgb(11, 6, 74)">CONTACT US FOR MORE DETAILS
                <h1>
                    <h4 style="color:rgb(0, 89, 255)">Phone no : 9867565739 <br> Email id : manojkumar123@gmail.com</h4>
                    <P style="color:rgb(255, 0, 0)">Address: 5/69 Anna salai, <br>karur main road,<br>trichy <br>
                        <p class="menu">Thank you for contacting us </p>
                        <br>
                        <p class="menu1">THANK YOU!</p>
                    </P>
        </section>
    </center>
</body>

</html>
~~~

## OUTPUT:
![Screenshot 2024-12-18 105531](https://github.com/user-attachments/assets/c240a355-885b-46b3-b4ab-29e978e5735c)
![396776003-fe322fcf-6df7-427b-afe9-cf0ffd219fba](https://github.com/user-attachments/assets/fd197247-d19f-4e0f-b7af-49ec63232117)
![Screenshot 2024-12-18 105617](https://github.com/user-attachments/assets/ccd1affb-7e68-49ea-999b-5fa59c95a582)
![Screenshot 2024-12-18 105643](https://github.com/user-attachments/assets/f1105dc5-afcb-4c0c-82e2-eb2c64284fc4)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
