# Ex.07 Software Product Company Website
## Date: 28.04.2024

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

main.html



<html>
<title>TECH BITES</title>
<style>
    body{
        background:url(ai.jpg) ;
        background-size: cover;
        
    }

    h1{
        color: rgb(154, 220, 47);
    }
    h2{
        color: rgb(28, 173, 235);
    }
    h3{
        color:tomato;
        align:center;
    }

/* the main window options*/
.styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #dca610; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:rgb(24, 198, 237); /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #60a6eb; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#eb8484; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}

.login{
    margin-top: -100;
    margin-left: 1100;
    margin-right: 100;    
    background:url(123.jpg);

    scroll-padding-left: 5px;
    border:2px solid rgb(75, 18, 181);
}
.login input[type="button"] {
    padding: 10px 20px; /*  button size */
    background-color: #3498db;
    color: #35e66a;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.login input[type="button"]:hover {
    color:#000;
    background-color:rgb(204, 32, 204);
}
.login input[type="submit"]{
    padding: 10px 15px; /*  button size */
    background-color:#4234db;
    color: #e614c6;
    border-radius: 10px;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.login input[type="submit"]:hover {
    color:#000;
    background-color:chocolate;
}
.login input[type="text"] { 
    padding: 10px; /* Add padding for better appearance */
    transition: background-color 0.3s; /* Add transition for a smooth effect */
        /* Set initial background color */
        background-color: #cddf31;
}
.login input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:slateblue; /* Adjust the color as needed */
}
.join{
    padding: 10px 20px; /*  button size */
    background-color: #3498db;
    color: #993232;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.join:hover {
    color: aquamarine;
    background-color: #4234db;
}

/main html/
</style>
<body >
    <form class="styled ">
        <div class=>
            <a href="main.html">
                <input type="button" value="HOME">
            </a>
            <a href="project.html">
                <input type="button" value="OUR PRODUCTS">
            </a>

            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>

    <h1>WELCOME TO TECH BITES</h1>
    <h2>one of the most trusted and valuble company</h2>
    <h2>PROJECTS</h2>
    <a href="sign.html">
        <input type="button" value="JOIN US" class="join">
    </a>  
    
    <h3>"A Realisation is a Boat"</h3>

         <center>
        <div class="login">
            <div class="login-box">
            <p style="color: rgb(36, 224, 30);">DONT HAVE AN ACCOUNT</p>
            <a href="sign.html">
                <input type="button" value="SIGN IN"><br><br>
            </a>  
            <p style="color: rgb(52, 146, 228);">LOGIN</p>
            <input type="text" value="Username or email" ><br><br>
            <input type="text" value="Password"><br><br>
            <a href="project.html">
                <input type="submit" value="SUBMIT"><br><br>
            </a>  
        </div>
        </div>
    </center>

</body>
<footer style="background-color:dodgerblue;margin-top: 210; border: none;">
    <P style="color:black ;"align="center">Designed and Devoloped by NAVEEN K </P>
</footer>
</html




project.html




<html>
    <title>our products</title>
    <style>  
    body{
        background:url(front.webp);
        background-size:contain;
    } 
    h1{
        color: rgb(113, 183, 244);
    }  
    .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #e65858; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:rgb(45, 126, 198); /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ae1111; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#733ae5; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:rgb(248, 153, 36);
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}
</style>
    
    <body>
        <form class="styled ">
            <div class=>
                <a href="main.html">
                    <input type="button" value="HOME">
                </a>
                <a href="project.html">
                    <input type="button" value="OUR PROJECTS">
                </a>
                <a href="about.html">
                    <input type="button" value="ABOUT US">
                </a>
                <a href="sign.html">
                    <input type="button" value="SIGN IN">
                </a>
                <a href="contact.html">
                    <input type="button" value="CONTACT">
                </a>  
                <input type="text">
                <input type="submit"value="SEARCH">  
            </div>
        </form>
        
        <center>
            <h1 >OUR PRESTIGEOUS PROJECTS</h1>
        <img src="proj.jpg" height="500" width="800">
    </center>
    </body>
    <footer style="background-color:dodgerblue;margin-top: 150; border: none;">
        <P style="color:black ;"align="center">Designed and Devoloped by NAVEEN K </P>
    </footer>
</html>




about.html




<html>
<title>about us</title>
<style>
    p{
        color: rgb(240, 148, 27);
    }
    body{
        background:url(back1.jpg);
        background-size: cover;
    }
    .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #d23939; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:rgb(25, 126, 215); /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #159eb9; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#5318da; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:rgb(243, 163, 66);
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}
.photos{
    display:flex;
    justify-content: space-around;
    margin-top: 200px;
}
.names{
    display:flex;
    justify-content: space-around;

}
.position {
    display: flex;
    justify-content: space-around;
    margin-left: 10px;
    border-image:5px;
    border-image: rgb(233, 154, 51);
}

</style>
<body>
    <form class="styled ">
        <div class=>
            <a href="main.html">
                <input type="button" value="HOME">
            </a>
            <a href="project.html">
                <input type="button" value="OUR PROJECTS">
            </a>
            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>
    <div class="photos">
    <img src="msd.jpg" height="200" width="200">
    <img src="virat.jpg" height="200" width="200">
    <img src="sachin.jpg" height="200" width="200">
    <img src="rohit.webp" height="200" width="200">
    <img src="suresh.webp" height="200" width="200">
    <img src="shami.jpg" height="200" width="200">
</div>
<div CLASS="names">   
    <P style="margin-left:-20;">MR MSD</P>    
    <P>MR VIRAT</P>    
    <P>MR SACHIN</P>    
    <P>MR ROHIT</P>    
    <P>MR RAINA</P>    
    <P>MR SHAMI</P>    
</div>
<DIV class="position">
    <p style="margin-left:40;">CEO </p>
    <p style="margin-left:60;">CO-FOUNDER </p>
    <p>CO-FOUNDER </p>
    <p>DIRECTOR </p>
    <p >CO-DIRECTOR</p>
    <p>EXEC-DIRECTOR </p>

</DIV>
</body>
<footer style="background-color:dodgerblue;margin-top: 210; border: none;">
    <P style="color:black ;"align="center">Designed and Devoloped by NAVEEN K </P>
</footer>
</html>




sign.html




<!DOCTYPE html>
<html>
<head>
    <title>Sign Up</title>
    <style>
        body {
            background:url(tech.jpg);
            background-size: cover;
            color: rgb(247, 144, 9);
            font-family: Arial, sans-serif;
        }

        .form {
            margin: 0 auto;
            width: 300px;
            padding: 20px;
        }

        label {
            color: chocolate;
        }

        .purpose {
            color: aqua;
        }

        .buttons {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #3498db;
            color: #e00f0f;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
        }

        .buttons:hover {
            color: aqua;
            background-color: #4234db;
        }
        .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #6c15ed; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:rgb(21, 126, 218); /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #f66868; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#c8f612; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}
.text{
    transition: background-color 0.3s, color 0.3s;

}
.text :focus{
    background-color:skyblue;  
}
.full{
    background:url(bg3.jpg);
    padding: 10px;
    border:4px double rgb(235, 242, 29);
}
    </style>
</head>
<body>
    <form class="styled ">
        <div class=>
            <a href="main.html">
                <input type="button" value="HOME">
            </a>
            <a href="project.html">
                <input type="button" value="OUR PROJECTS">
            </a>
            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>
    <div class="form">
        <p align="center">JOIN THE FAMILY OF HPKSOFCO</p>
        <p align="center">DON'T HAVE AN ACCOUNT YET?</p>
        <div class="full">
        <div class="text">
           
        <label>Unique Username</label>
        <input type="text" value="username"><br><br>
        <label>Email</label>
        <input type="email" value="email"><br><br>
        </div>
        <label>DOB</label>
        <input type="date"><br><br>
        <label>Gender</label><br>
        <div class="purpose">
            <input type="radio" name="gender">Male<br>
            <input type="radio" name="gender">Female<br><br>
        </div>
        <label>Purpose</label><br>
        <div class="purpose">
            <input type="radio" name="purpose">Study<br>
            <input type="radio" name="purpose">Work<br>
            <input type="radio" name="purpose">Partnership<br><br>
        </div>
        <label>Click the checkbox to prove you are human</label>
        <input type="checkbox"><br><br>
        
            <input type="submit" value="CREATE ACCOUNT" class="buttons">
            <input type="submit" value="DOWNLOAD SOFTWARE"class="buttons">
        
    </div>
</div>
</body>
<footer style="background-color:dodgerblue; border: none;">
    <P style="color:black;"align="center">Designed and Devoloped by NAVEEN K </P>
</footer>
</html>



contact.html



<!DOCTYPE html>
<html>
<head>
    <title>Contact Us</title>
    <style>
        b{
            color:cornflowerblue
        }
        p {
            color: rgb(31, 139, 234);
        }

        body {
            background:url(green.png);
        }

        .yourinfo {
            background:url(bg3.jpg);
            border:5px solid rgb(232, 71, 71);
            margin-right: 800px ;
            
            margin-top: 200px; /* Adjusted margin-top */
            padding: 10px; /* Added padding for better spacing */
        }
        .yourinfo input[type="text"] {
            width: 500px;
            transition: background-color 0.3s; 
        }
        .yourinfo input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color: #2278c3; /* Adjust the color as needed */
}

        .buttons {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #3498db;
            color: #831212;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
        }

        .buttons:hover {
            color: aqua;
            background-color: #4234db;
        }
        .styled form {
            display: flex;
            justify-content: space-evenly;
        }
        .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #12e660; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:rgb(175, 224, 14); /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #eb10bb; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#ac18e7; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}
    
.company{

margin-left: 900px;
margin-top: -330px;
background:url(bg5.jpg);

scroll-padding-left: 5px;
border:2px solid rgb(237, 9, 9);
}
.message textarea {
        background-color: rgb(118, 24, 234); /* Set the default background color */
        color: black; /* Set the default text color */
    }

    /* Styles for the text area when it is in focus */
.message    textarea:focus {
        background-color: cadetblue; /* Set the background color when in focus */
        color: rgb(245, 78, 217); /* Set the text color when in focus */
    }
    </style>
</head>
<body>
    <form class="styled">
        <div>
            <a href="main.html">
                <input type="button" value="HOME">
            </a>
            <a href="project.html">
                <input type="button" value="OUR PROJECTS">
            </a>
            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
        <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>
            <input type="text" >
            <input type="submit" value="SEARCH">
        </div>
    </form>
    <div class="yourinfo">
        <center>
        <p>Contact Information</p>
        <div>            
            <input type="text" maxlength="100" placeholder="Your Name"><br><br>
            <input type="text" maxlength="100" placeholder="Your Email"><br><br>
            <div class="message">
            <textarea rows="5" cols="65" placeholder="Your Message"></textarea><br><br>
        </div>
            <input type="button" value="SUBMIT" class="buttons">
        
        </center>
        </div>
    </div>
    <div class="company">
        <center>
        <h3 style="color: rgb(12, 130, 233);">COMPANY CONTACT INFORMATION</h3>
       <p> <b >Address</b></p>
        <p >66,Annamayya Circle</p>
        <p >Nellore</p>
        <p >ANDHRA PRADESH-524003</p>
        <b >Email:</b>
        <p >abcdef@gmail.com</p>
        <b >Phone</b>
        <p >9876543210</p>
    </center>
    </div>
</body>
<footer style="background-color:dodgerblue;margin-top: 200px; border: none;">
    <P style="color:black ;"align="center">Designed and Devoloped by NAVEEN K</P>
</footer>
</html>




```

## OUTPUT:


![alt text](<Screenshot 2024-04-28 152720.png>)
![alt text](<Screenshot 2024-04-28 152732.png>)
![alt text](<Screenshot 2024-04-28 152745.png>)
![alt text](<Screenshot 2024-04-28 152757.png>)
![alt text](<Screenshot 2024-04-28 152805.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
