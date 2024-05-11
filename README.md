# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Product Page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(background.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-product {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                border-radius: 30px;
            }
            .logo {
                color: #6fa1f8;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .container {
                background: transparent;
                padding: 10px 5%;
                padding-bottom: 100px;
            }
            .container .box-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 20px;
            }
            .container .box-container .box {
                color: white;
                box-shadow: 0 5px 10px rgba(0,0,0,.2);
                border-radius: 20px;
                background: transparent;
                border: 1px solid white;
                padding: 30px 20px;
            }
            .container .box-container .box img {
                height: 70px;
                border-radius: 20px;
            }
            .container .box-container .box h2 {
                color: #6fa1f8;
                font-size: large;
                padding: 10px 0;
            }
            .container .box-container .box p {
                color: white;
                font-size: small;
                line-height: 1.5;
            }
            footer {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">T<span>ech</span>C<span>omrade</span></h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="product.html" class="bg-product"> Products </a></li>
                <li><a href="person.html"> person </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="container">
            <div class="box-container">
                <div class="box">
                    
                    <h2> CodeForge Pro </h2>
                    <p> Streamlined collaborative coding platform. </p>
                </div>
                <div class="box">
                   
                    <h2> SiteGenie Builder </h2>
                    <p> Simplified drag and drop website creation. </p>
                </div>
                <div class="box">
                    
                    <h2> DevSync Hub Pro </h2>
                    <p> Efficient version control and sync. </p>
                </div>
                <div class="box">
                    
                    <h2> WebOptiMate Suite </h2>
                    <p> Enhanced web performance optimization. </p>
                </div>
                <div class="box">
                   
                    <h2> CodeLeap Toolkit </h2>
                    <p> Tools for innovative web development. </p>
                </div>
                <div class="box">
                    
                    <h2> SiteGuard Pro Shield  </h2>
                    <p> Robust multi-layered website security. </p>
                </div>
                <div class="box">
                    
                    <h2> WebFlow Pro Studio </h2>
                    <p> Rapid low-code app creation. </p>
                </div>
                <div class="box">
                   
                    <h2> DevInspect Test Kit </h2>
                    <p> Automated testing and debugging. </p>
                </div>
                <div class="box">
                   
                    <h2> SiteSphere CMS </h2>
                    <p> Streamlined web content management. </p>
                </div>
                <div class="box">
                    
                    <h2> CodeBoost Accelerator </h2>
                    <p> Optimized code efficiency tools. </p>
                </div>
                <div class="box">
                    
                    <h2> WebScale Pro Manager </h2>
                    <p> Seamless high-traffic handling. </p>
                </div>
                <div class="box">
                   
                    <h2> DevSphere IDE Suite </h2>
                    <p> Integrated tools for developers. </p>
                </div>
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by Sanjit P(212223230190) </center>
    </footer>
</body>
</html>

```


## OUTPUT:
NAME:SANJIT P
REGISTER NO:212223230190
![Screenshot 2024-05-08 090258](https://github.com/Sanjit2328/Pharma/assets/139331694/6c97ee58-ac6b-4d00-a406-7c549a44accb)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
