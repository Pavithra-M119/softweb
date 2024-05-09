# Ex.07 Software Product Company Website
## Date:5-5-2024

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
### home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
    <style>
        *{
            margin:0;
            padding:0
        }
        #nav{
            background-color:teal;
            color:white;
            padding: 15px;
    
        }
        li,h1,ul{
            display:inline;
        }
        ul{
            margin-left:60%;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
       
        }
        
        .box {
            display:inline-block;
            border-style:dotted ;
            border-radius: 10px;
            border-color: yellow;
            width: 400px;
            min-height: 300px;
            font-size: 20px;
            background-color:teal;
        
        }
        .heading1{
            color:black;
            text-align: center;
            padding-top: 20px;
        }
        .heading2{
            color:rgb(27, 23, 23);
            text-align: justify;
            font-size: 30px;
            margin-left: 30px;
        }
        .edge{
            padding-left: 900px;
        }
        .box{
            text-align: center;
        }
        .bottomdiv{
            background-color:teal;
            color:white;
            text-align: center;
            position:fixed;
            bottom:0;
            width:100%;

        }
        table{
            margin-left: 40px;
        }
    </style>
</head>
<body background="company img.png">
    <div class="header">
        <nav id="nav">
            <h1>
                HatTrick crafts
            </h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">People  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
        </nav>
    </div>
    <div class="searchbar" style="border-radius: rounded-5;">
    <input placeholder="Search">
    </div>
        <div><pre class="heading2"><b>
"Crafting Code, Grafting Solutions:
Your Vision, Our Mission."<b></pre></div>
        <div class="edge">
            <div class="box">
                <div class="login">
                    <form>
                        <h3>Login Here</h3>
                        <input type="text" placeholder="Username or Email"><br><br>
                        <input type="password" placeholder="Password"><br><br><br>
                        <button>Login</button>
                        <h5>Don't have an account?</h5><br>
                        <div class="Signup"><b><a href="" >Sign up</a></b> here</div>
                        <h5>Login with</h5>
                        <div class="image">
                            <img src="facebook.png" width="25px">
                            <img src="insta.png" width="25px">
                            <img src="twitter.png" width="25px">
                            <img src="google.png" width="25px">
                        </div>
            
                </div>
            </div>
        </div>
    <div class="bottomdiv">
        <p>Designed and Developed by Pavithra.M(212221040119)</p>
    </div>
</body>
<html>
```
## product.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PRODUCTS</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:teal;
            color:white;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:60%
        }
        li{
            color:black;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:rgb(198, 239, 144);
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:rgb(27, 30, 30);
            cursor:pointer;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:white;
        }
        .bottomdiv{
            background-color:rgb(224, 220, 13);
            color:white;
            text-align: center;
            position:fixed;
            bottom:0;
            width:100%;
        }
    </style>
</head>
<body background="company img.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">HatTrick Crafts</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">People  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2" style="color: black;">PRODUCTS</h1>
        <br>
        <div class="product">
            <div class="box">
                <img src="adobe.jpeg" width="200px">
                <h1>Adobe Creative Cloud Suite</h1>
                <p>Photoshop, Illustrator & More.</p>
            </div>
            <div class="box">
                <img src="maple.jpeg" width="200px" height="200px">
                <h1>Maple</h1>
                <p>Statistical Package</p>
                </div>
            <div class="box">
                <img src="sas.jpeg" width="200px" height="200px">
                <h1>SAS</h1>
                <p>Statistical Analysis System.</p>
                </div>
            <div class="box">
                <img src="matlab.jpeg" width="200px" height="200px">
                <h1>Matlab</h1>
                <p>Coding Software</p>
                </div>
            <div class="box">
                <img src="pycharm.jpeg" width="200px">
                <h1>Jetbrains Pycharm</h1>
                <p>Computer Programming</p>
                </div>
            <div class="box">
                <img src="office.jpeg" width="200px" height="200px">
                <h1>Microsoft Office Suite</h1>
                <p>Word, Powerpoint, Excel & More.</p>
                </div>
        </div>
    </div>
    <div class="bottomdiv">
        <p>Designed and Developed by Pavithra M(212221040119)</p>
    </div>
</body>
</html>
```
### person.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>People</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:teal;
            color:white;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:60%
        }
        li{
            color:black;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:gray;
        }
        .bottomdiv{
            background-color:teal;
            color:white;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 163px;

        }
        img{
            border-radius: 50%;
            width: 200px;
            display: inline;
            padding:3px;
        }
        .person{
            margin:100px;
            text-align:center;
            
        }
        b,p{
            color:rgb(32, 16, 16);
            text-align: center;
        }
    </style>
</head>
<body background="company img.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">HatTrick Crafts</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">People  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">PEOPLE</h1>
        <table class="person">
            <tr>
                <td>
                    <img class="small border" src="office1.jpeg" width="500px">
                </td>
                <td>
                    <img  class="small border" src="office2.jpeg"  width="500px">
                </td>
                <td>
                    <img class="small border" src="office3.jpeg"  width="500px">
                </td>
                <td>
                    <img class="small border" src="office4.jpeg" width="500px">
                </td>
                <td>
                    <img class="small border" src="office5.jpeg" width="500px">
                </td>
                <td>
                    <img class="small border" src="office6.jpeg" width="500px">
                </td>
            </tr>
            <tr>
                <td>
                    <b>Dhakshala</b>
                    <p>CEO</p>
                </td>
                <td>
                    <b>smriti Watson</b>
                    <p>CEO,Co-Founder</p>
                </td>
                <td>
                    <b>Efflin Stonem</b>
                    <p>CTO,Co-Founder</p>
                </td>
                <td>
                    <b>Monica chandlar</b>
                    <p>CEO Director</p>
                </td>
                <td>
                    <b>harini</b>
                    <p>Asst.Director</p>
                </td>
                <td>
                    <b>Julie</b>
                    <p>Dy.Director</p>
                </td>
            </tr>
        </table>
    </div>
    <div class="bottomdiv">
        <p>Designed and Developed by Pavithra.M(212221040119)</p>
    </div>
</body>
</html>
```
## contactus.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ContactUs</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:teal;
            color:white;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:60%
        }
        li{
            color:black;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:black;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:teal;
            cursor:pointer;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color: rgb(37, 37, 24);
        }
        .table1{
            color:gray;
            font-size: large;
        }
        .contactus{
            color:black;
            margin-left:400px;
        }
        .heading3{
            padding-top: 30px;
            padding-bottom: 10px;
            text-align: center;
            color:gray;
        }
        .table2{
            color:rgb(21, 21, 5);
            font-size: large;
            background-color:rgb(95, 92, 92);
            border-radius: 5px;
            border-style:dotted;
            border-color: white;

        }
        .queries{
            margin-left:600px;
        }
        .bottomdiv{
            background-color:teal;
            color:white;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 24px;

        }
    </style>
</head>
<body background="company img.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">HatTrick Crafts</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">People  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">CONTACT US</h1>
        <div class="contactus">
            <table cellpadding="15px" cellspacing="15px" class="table1">
                <tr>
                    <td>
                        ADDRESS :
                    </td>
                    <td>
                        A-95 Golden street, sugar mill,vellore-632 519
                    </td>
                </tr>
                <tr>
                    <td>
                        LANDMARK :
                    </td>
                    <td>
                        Near vellore fort
                    </td>
                </tr>
                <tr>
                    <td>
                        Email :
                    </td>
                    <td>
                        hattrickCraft@gmail.com
                    </td>
                </tr>
                <tr>
                    <td>
                        PHONE :
                    </td>
                    <td>
                        8976563772                        
                    </td>
                </tr>
            </table>
        </div>
        <div>
            <h3 class="heading3">QUERIES</h3>
            <div class="queries">
                <table cellpadding="15px" cellspacing="15px" class="table2">
                    <tr>
                        <td>
                            NAME :
                        </td>
                        <td>
                            <input type="name" placeholder="Enter Name"> 
                        </td>
                    </tr>
                    <tr>
                        <td>
                            EMAIL :
                        </td>
                        <td>
                            <input type="email" placeholder="Enter E-mail">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            MESSAGE :
                        </td>
                        <td>
                            <input type="text" placeholder="Enter text">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <div style="text-align:center;">
                            <input type="submit" style="background-color: lightskyblue; color: black;" >
                            </div>
                        </td>
                    </tr>
            </table>
        </div>
        <div class="bottomdiv">
            <p>Designed and Developed by Pavithra M(212221040119)</p>
        </div>
    </div>
</body>
</html>
```

## OUTPUT:
![Screenshot (35)](https://github.com/Pavithra-M119/softweb/assets/119229774/503922fb-46ef-40a9-892a-25f46050a8fa)
![Screenshot (37)](https://github.com/Pavithra-M119/softweb/assets/119229774/ffe67d78-bceb-4b85-a27a-ff4787736378)
![Screenshot (36)](https://github.com/Pavithra-M119/softweb/assets/119229774/36c98437-e012-4b64-9f28-826cf55378df)
![Screenshot (38)](https://github.com/Pavithra-M119/softweb/assets/119229774/c8c868f9-66be-42a0-8341-d692b3ac6e95)




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
