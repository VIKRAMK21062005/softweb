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

## Code:

```
home.html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Home Page
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/style.css">
    <style>
    .text{
        color:purple;
        font-family:'Gill sans MT';
        font-size: 30px;
        text-align:center;
    }
    img{
        
        height:200px;
        width:200;
        position:center;
    }
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: yellow; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="product.html" title="Products" style="color:yellow; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:yellow; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:yellow; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1 face="cursive">Zoho Corporation</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <marquee><b>Make your future bright by developing your skills. </b></marquee>
                    <p style="color:orange; font-family:'Tahoma'; font-size:20px;"> This is the Official Website of our Zoho Corporation.</p>
                    </div>
                    
                    <div class="content1" font="cursive">Software developers are the creative force behind computer programs of all kinds.<br>They design and write the code used to build everything from operating systems to apps to video games.<br>A Software Developer designs and builds computer programs that power mobile devices, desktop computers, and even cars.<br>Software developers need to stay up-to-date on the latest advancements regarding the tools, frameworks, programming languages, and apps to achieve success.<br>You can learn from<span style="background-color:lime">Zoho Corporation</span>
                         for Rs.1000 | Get free certificate | Intenship programs | Workshops | Hackathons | And much more...
                        <img src="https://www.maven-infosoft.com/wp-content/uploads/2014/01/iphone-and-ipad-app-development.jpg"></div>
                    
                    <br>
                </div>
                <div class="footer">
                <h2><footer style="color:black">
                Copyright &copy;2023 Developed by VIKRAM K</footer></div>
            </div>
        </div>
    </body>
</html>

product.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Products
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/style.css">
        <style>
        .home{
            height: 1260px;
            width: 70%;
            border: 12px solid lawngreen;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:cyan;
        }
        .text{
            color:blueviolet;
            font-family:'Lucida Sans';
            font-size: 30px;
            text-align:center;
        
        }
        .content{
            border:3px solid darkblue;
            background-color: white;
            width:90%;
            height:900px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ph1{
            background-image: url(https://cdn.thenewstack.io/media/2021/11/ab06a958-pythonlogo.png);
            background-size: 300px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 50px;
        }
        .l1{
            color: crimson;
            position:relative;
            right:320px;
            
            
        }
        .ph2{
            background-image: url(data:image/jpeg;base64,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);
            background-size: 350px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 50px;
            
        }
        .l2{
            color: crimson;
            position:relative;
            right:320px;
        }
        .ph3{
            background-image: url(data:image/jpeg;base64,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);
            background-size: 350px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 50px;
            
        }
        .l3{
            color:crimson;
            position:relative;
            right:330px;
        }
        .ph4{
            background-image: url(data:image/png;base64,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);
            background-position-x: center;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 600px;
            bottom: 796px;
            background-size: 390px;
            background-repeat: no-repeat;
            
            
        }
        .l4{
            color: crimson;
            position:relative;
            left:250px;
            bottom: 796px;
        }
    
        .ph5{
            background-image: url(data:image/jpeg;base64,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);
            background-position-x: center;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 600px;
            bottom:796px;
            background-size: 300px;
            background-repeat: no-repeat;
            
            
        }
        .l5{
            color: crimson;
            position:relative;
            left:250px;
            bottom: 796px;
        }

        .ph6{
            background-image: url(https://monkfox.com/wp-content/uploads/2019/03/maxresdefault-8-2.png);
            background-position-x: center;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 600px;
            bottom:796px;
            background-size: 300px;
            background-repeat: no-repeat;
            
            
        }
        .l6{
            color: crimson  ;
            position:relative;
            left:250px;
            bottom: 796px;
        }
        .bot{
            text-align:center;
            font-size:larger;
            

        }

        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color:yellow; text-decoration: none;"><b>Home</a></div>
                    <div class="prod">
                        <a href="product.html" title="Products" style="color: yellow; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:yellow; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:yellow; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Products</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>These are the programming languages that are available now</p>
                    </div>
                    <div class="ph1"></div>
                    <div class="l1"><p align="center"><b>Python program<br> Price: 2500.00</b><br><br><br><br></p></div>
                    <div class="ph2"></div>
                    <div class="l2"><p align="center"><b>Blockchain<br> Price: 3000.00</b><br><br><br><br></p></div>
                    <div class="ph3"></div>
                    <div class="l3"><p align="center"><b>HTML<br> Price: 1999.00</b><br<br><br><br></p></div>
                    <div class="ph4"></div>
                    <div class="l4"><p align="center"><b>Microsoft<br> Price: 6999.00</b><br><br><br><br></p></div>
                    <div class="ph5"></div>
                    <div class="l5"><p align="center"><b>Kotlin<br> Price: 7999.00</b><br><br><br><br></p></div>
                    <div class="ph6"></div>
                    <div class="l6"><p align="center"><b>PHP<br> Price: 5999.00</b><br><br><br><br></p></div>
         
                </div>
                <div class="bot"><p>To Order Online: Call 80 60 40 2004</p></div>

                <div class="footer">
                <h3><footer style="color:black">
                Copyright &copy;2023 Developed by VIKRAM K</footer></h3></div>
            </div>
        </div>
    </body>
</html>

people.html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            People
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/style.css">
        <style>
        .home{
            height: 2540px;
            width: 85%;
            border: 12px solid lawngreen;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:cyan;
        }
        .text{
        color:black;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
        
        }
        .content{
            border:2px solid blue;
            background-color:white;
            width:98%;
            height:2240px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ceoph{
            background-image: url(/static/images/myphoto.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:3px solid red;
            height:200px;
            width:200px;
            position:relative;
            left: 0px;
            margin-left:auto;
            margin-right: auto;
        }
        .ceo{
            color:black;
            position:relative;
            text-align:center;
            
            
        }
        .manph1{
            background-image: url(https://media.licdn.com/dms/image/C5103AQEjn9n78lkgSw/profile-displayphoto-shrink_800_800/0/1585728648959?e=2147483647&v=beta&t=gikgBWdg8FFee44ucXKfrvewFzeNlKTj3ijrFqkicmQ);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:200px;
            position:center;
            margin-left:auto;
            margin-right:auto;            
        }
        .man1{
            color:black;
            position:relative;
            text-align:center;
            
        }
        .manph2{
            background-image: url(https://cdn.vox-cdn.com/thumbor/Ej5TsHlL2cxiOcdKl_EyOpNpd4Y=/1x0:1018x678/2050x1367/cdn.vox-cdn.com/assets/1241553/mayer-1020.jpg);
            background-size: 350px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:200px;
            position:center;
            margin-left:auto;
            margin-right:auto;

            
        }
        .man2{
            color:black;
            position:center;
            text-align:center;
        }
        
        .amph1{
            background-image: url(data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAoHCBUWFRgVFRUYGBgaGBgYGRgYGBgYGBgYGhoZGRgYGBgcIS4lHB4rIRgYJjgmKy8xNTU1GiQ7QDszPy40NTEBDAwMEA8QHhISHjQhISQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQxNDQ0NDE0NDQ0MTQ0NDQ0NP/AABEIAOEA4QMBIgACEQEDEQH/xAAbAAABBQEBAAAAAAAAAAAAAAADAAECBAUGB//EAD4QAAIBAgQCBwUFBgYDAAAAAAECAAMRBBIhMQVBIjJRYXGBkQYTobHBQlJy0fAHFDNiouEVI4KSsvE0Y3P/xAAaAQADAQEBAQAAAAAAAAAAAAAAAQIDBAUG/8QAIxEAAwACAgMAAgMBAAAAAAAAAAECETEDIQQSQTJRE2GhIv/aAAwDAQACEQMRAD8A86pDWWisrUt5czS2ZyNwqkSzHvmgBKHDKpzMJoZIkUy+o6EoqZbamckqUxGjOiVpu4YdETDtNzC9UQZI9QQVAaw7CKnTtAMhaUr4xGbaX8PThwgmdTliyc5/hbvvLFLgqjfWa9Ssi7so8SBEHB2IPgQY1KE2ypTwCLyEOtMDYR2MYNLRORwsMqwN4RXgwySyxyJHPGLxYDI8gxjZoxlBkFWGsARLFYQNpc6IrZAiNaTIjWlEkbRWkrRjJAaKPFAZwKbyyRKw3llzM2da2R4d12mqDMXA1LOZqJVvpEimbCfw5TopflNPC0roLyxSoKOUaRnVGfTwJM1aNGwtCKJNYyMiFOM9lFybCO727fIXmdisWFYFiNL+H6/vBvBcS2Eq8SIHRsg7XGp8BeYuMxzucpdyL6kWHd2AfOWnemz52YE2F7hj2WHeb+XZeKrjlXROiOZ0uey2nfvpJZuoS0YGJwwW4Abe5Lanz008gZTfDMrXDW1uLZge07CwmlUxABuQWPK5sPHff85m1HYnTNc6b8jawXbvkseA68YxNO2V2ZRfrjMLDtJ1E2+E+1CuQlbKh5MD0Sewg9Wcy6jRSWvc68he6i1tzoTfneCehpm5ajNY3zWv9QI0zOoTPUEa4uDcdo2PhCATgfZvjxpt7uoegTYX+xc737J3itKTyc1T6slaK0ePeMRC0cCOITLAEivWEARD1t4Ey50TWyJEa0kYpRJG0YiStGMAGiiiiA8/EtMLgSsJZU9GZM652VMKvTM6LBYbmZicMW9UzqaYiRVM0aA6IhVEhR6ohAJSMa2SEmJAQiPbpWvbW3hGSll4M3jWLFIBM1nfcfdTX5/SYeGoPVOZQWPI8l56fD0mrw3Cviq4d1JW+UHlZQLnuucxnfYbg6IAFA8ALD0nPdtaPT4uFNd6PNG4ZXH2W8jb5SCcIrnQLe/dt5kT1oYRfuiSGGUbKPSZ/wAlG/8ADJ5O/syxN3c382t+QlN+C5T0cxPh9Z63icArcvT5TPqcLQDaS7f0pcMvRwdLgGZMwHw5/q/9pn1KAOZGsNefV3IFu3VmnpAoALYbWGk5TjPDekXFuZK33HMjv5w4uZuvVi5uBKfZHA47DFHI+O3Mkees7L2S4gXT3bHpJtfcry8bbTneLo5CsuugU8r5bZdOVsvwkeA4spXQ33YKewgnL+RnUtnm3OUekiK0HeGSUcolAjmK0e0CirWGsEYeuNYEzSdGV7Ixo5itKENFHtImSAooooDPPwdJYTqysu0s4fYzM6vpDhP8UzqUnMcKH+cZ1CRIb2aVHqiEEhQ6ohBKRjWxxFWW6MO1SNr8o4k0OsbCemjT9mKoFNAALkAHTXQa387zqKSk6mc3wGkEbO3UF7H7zWuT6mT4p7WKlwq3tzH9px13TPZnqUdQSJCwnAL7cZjbI/jYzoOD8QaslwLHn3GZOmnho0mU1lM3HyyliKXZOW4txiujsqgWtoTveYtLjOMdusgH4rRY9is+h2dRDznN8bpsQwU6iNW4rXXrD4iAoYv3j3B8QdCPKQpcvKKdK16v6ck9Ik630JJHeO0eF5WNMCohyjrIW0t9obeU6rFYWzlgu4N/Ua/rtmNUo2Kk6gsNDbe/Lstr6TtisrJ5vLHq2jsQIRWjhY4Sbnn4FmiLRERosCBV94Ew1feBM0WiK2NFHjRiFImSjWiAjFHtFAZ57T2ljDc5WpbSxhzrIOkXCv4xnVIJyvCj/ntOqWSins0qPVEIIOiejCCUjKtkxCUKZdlUbkgdg9YOJT27cx2jmIPXQpxlZ0dFxxCtJEXTXW3ZONxNR1OWlTzW3dh0b+M9HwQVqa5jcgAXve9tCbmBxnBs3VZl/CbThrt5PanCWDzKnhcS/ScImmwYG5vtoTb0PhO79lcI1KgxJ1LXHdoBb4GWU4IiAsbs1t2Nz5TUoFVp5TYG235yX3vo0xhddnHYzBiq7Fhe9wNba8piYr2fTKVYupuDmIta3IFRlt5Tp6985y2Ivy38pu0qYZQSAdJnx010a8kp7POML7PEMPc1nYXNwekg7jcW8hN+jwcJ0m61uwCdcKCqNAAZicRe1/OF00TEr4c3iui4A9JUSgAGKKGZRcEi4UadK3buBJcSc5jY6yxw9GUlt0YamxzAHn4X08pXu1x4EoT5chOHqwDK5vY6HbQ6y0TE4ynLzAAPiLj5WkJ28OfRZPG8vC5ngcmMohQukhlmpgBr7wULX3gpa0Z1saNHMYyiRRRCORJGhooooDPOqcNS3gU3MKm8g6WT4V/HbynVLOV4Z/HPlOqWShs0KPVhVgqI6IhllIyrZKIR4hGQdLwTEdFSeVx5ia748TleFvZW8R8f+odapO5sJ5nK3NtI97x0r41VGrUxpY2W2ms5z/Fal2DrlOZrcgR2Xvrz1EavxYIcocKLm/MnS5J7BcD1lPE+7qkt7xlHRtYKw0IJOp52+MpRlZpmns84lEaOLq5zlK5SRodBqL9E7mddh3KotjewsfracirIosuZ9rE2LWAsBYXG0rJxSpnCor6G56L2A00udOXbE4XwHVL8kdticfYTCx+JvI4Wv74NfTLvfTXaCxCWEwpPPZtLWOjGrm73mxw8j3ROml9bm5H3QOQmPiBuZfwGLU0sgBJvZjbQa66+E0SdJSkY1Shum8dB0qFum27G9uwch6WkgZEmMGnqTPqsHz106p0/pY95GMgrRO8AQKsdYOEqQd5c6IrYjImOZEyiRwJJok3kniY1ohFFaKIeDzkdYwinWDfrSQOsg6GH4cP88+AnUoJzOA0rX7p1CPEM0KPVEmsbDi6iEyxozrYhHjZDJWjEW+HVbEryb5j/ALMu0wL2I0mQpIII3Gsve9BF5w+THfsj1PB5V6uX8KNPhFJndaiq6lzlDfdGuh87TUp4qjRGT3aqBoOhf5cpDDtdwBvpre3w5zSq06J6xHdqB6frnM17fDsVJGZV4qrdFF8LJlH5yeGQ21FieUJmp3AAsR3X7QRfyhquKUqCNNCfTxiabY/cz6AVM4AAu1/7fCVMXUvE+PzM3ht2Hu7pnYzFixtIqW6KmkpKmOqS7whLUwe0sfjMCo5Yzp+Gge6Xxb1udPl6zr4Fhnm+c/aU/wCyZjXk3EgZ15PLHVpYx2GCKjBr5uXle4lYysUOYa6CJlzjDyXKLoGUv1bi/hDcaaiHUUiLFbkDbuMqEyuE6V41kG59WvoUxooryjEkm8unBki8pUjqJ0VIjKIM0lZMf90aKbVxFJL9UeL1xqI15LEbiQMRbLuD/iKe6dGk57ALdlM6GnyiGbOEpsUuBJ2bslvh7koMtpdFLugmTUmKxaR96ZsVaIttMiutmjIpYJh4+cjaMg0jGDSawwmnLTQKtVYHMOQ6XaR2r27wT4+4OpO1rfZa4GpPL9eNyrQJRXt2i/ba35iZ9amRracjSl4fw9eW6lUvpNMcGIG1r5ezYD4/reBfE6aAEFyARcACw9Nb/oyGQcl/Wn5CDZGPKJ1JSigTVstyTdtRfzJlQlnPdLJwpJmnhMEBM3S+Gky2ZtLC21mj7KYOq/70SStM2CMLX95lAuoOhy28Dmt4XsPw/wB64RdFGrsOQ/M7CdNRpqihEACqLAD9bzr8Xjbbp6Oby6lJT9PPMJxh1qnD4kKrhsgcaIx+zfszAgg942m41JuycZ7boP3lxb7K39LC/kBG4B7W1aPQqD3qDa56ajsDHrDuPqJtXVNHnvjT7OyNJuyOKLdkucN4zh6ygo63P2WIVwewqdfpNZUUjaLJPocy+hkIXF9dvGAvLWjGtkjFIZos0CQlE9ITbWppMKidZpCpBmklv3kUq54oizy3EiDhsSNIGSaGtwl7TbUzA4UZupEI6jg1MFN7TS9x/NMLhvV3tLoB+9GkJst16Zt1piVutLdW/wB6Z7HWPBm2XE2gMfi1pIztyGg+8eQEhXxqINTr2DU/2mRg3OLx2Go7IaikjcZE6b38QhHnAuZbNvj1Z8PUwtJ+dMq/Z7xwHY+twO60d6RIuvpLP7SMKWLuB0kyVF8FPT/pzSrgK2ZFO9xOXyZ9Wn+0et4rzOP0BTTRlt8pI0yToNJbZu6RDGcbZ2KQKYXW50lqjTZ2CINeZ5AcyY1DDvUYIguT5DvJ7p1eA4etJLDVj1m+8foO6dPj8L5Hl6Ofn5lxrC2Dw2FWkmVfEk7se0yoj6kzSrDSYfFK3u6NR+aozegNp7EpJYR5NNt5Z5R7SYr3uJquNi5A8F6AP9MyVGssOsBOOnl5KCjtmhg+LVqdslR1HZclf9p0mekeIDoaftG/21Vu/qn4afCXKfHaZ3DL8R8Jyl5INGqaIfHLOyTiNNtnXzNvnDhwdpw+eFpYhl2JHgSI/Yh8C+M7ii2suhpxWG42672bxH1E1KPtCp6yEeBv8DHlE/x0jos8Ux/8bpfePoYoB61+jkKw0gBtLL7GVV2kmpf4U3Sm8jzm+HPZptipECOj4eoK7y2U75gUceiJqTfsH5yriOLudjlHdv6ykJy2zdxldUGra9nOYWJ4kT1Tbv5zMqYknnBB7wyUoSLJqEzU9isR7rEVMTYN7qi1gds7kKl+7KHPlMdtF7z+rSzw+/7piiNLvRS/iKgPwaVCy+yq6R13A/aF8elRqyoHQqDlFgadQMASO4gg+ImXwksgyHdSVPipsflF7LYg4bMAitmXQ2GYEDVb/aRtAVvyuNRNrFYBHT94o3yk3dT1kPP0O/kZPlcTc5xo38XlU1hvZYQ5hsI1rkADUm3rAYbMBD5ipDDcEEeI1E8rCyerno1aWIGFF3UMDb3jKDnU93JlHYNefdNhKyuodGDKRcMDcGVBUSsgOUtcEFeStzB+c5XEYt8FUJFyjHWmeZ/l1Nj3z3eOZ9F6nh8lU7brZ12I2nJe2tbLhnF9WKr6kE/AGdJheIU66Z0PiDoynsYTgf2g4u7pTGy3v3tYfK9vWVTxLI2ziGMhlvJNEJxlkQLQLVSxyr5nkPzlgi+hkVQAWEAEsRMRg2MAJZpJWgrxw0CguaJqloMmDqmBJP3seVbxQA13Mp3lljA4ZbuB339NYEpFjCUSDcm1uXPXlLpryiH1bxvJBoFJB3rXgnqSDNIJ2wKDZbje0nTgWaEQwAsudJscERThmQg5qlVXGmhykqfS3xmJUPRneeyWEDUaII+yW/3MT9Z0cK7IrQ+HwGo0mnhy1E6BbN94dHXdTzAOk3EwY7ITEcODCxG4mzpaISOcyAE2Fv5Tuvd3jvkalpbbCshyVLldclUalO5+1e+UKuKtog1+9bb8IO3jv4Ti5PCVVmH0zujzMTitr/RHGNQVtSC9rJzsL9Ijlf5DwlPDYJ6zZ6hv2DkIyYVme7XJ3JPaZ0mBw+UDSdsQuOVKOO6fJTpmQnCaiOHpHK23cR2EcxOG9rXP7wyFsxQBSe1j0n/qYjynrdZwisx0Cgk+AFzPEOIVy7u53dmY+LEk/OZc1dYCV2VLxRSU5ihARERxA4t7LYbnT84ACptcluWw8I7GJVsJFoANHBjRGIokG3MC5knOgg4EjRR7RQA0mMjheufwn5iO5j4Uase4fr4Rghs3SMIkA56frDIdIFCfUx9ok7YzmACBhkMADCo0EAasejPTvZBbUqX/AMk+KgzzCsejPUvZX+DTP/rT/gs6OH6RXw7HDppLWTSBoWCiF95pflJpvI0Y/HblQg5m58tvj8pUNBWphQnSBBvlAy2Gtm3a+npL2JGZ7iGSnpNV0kT9MXD4HpHT9WmmKNpZoILHxPzkiIOssEjlfbXFe7wrjm9kH+rrf0hp49VOs9D/AGmYzpJTvsC58+ivyaedMZhyPLGhhJRhHAmYxxKebMxbkNB9TDYupYZRu3y5mCQWEAHcwV47NB5oATBiJ5SN4lOsQCc6yMZjrFeADxSOaKA8mixhMKNGPeP18YFjD4fqnx/KMEArdYeMKp0gMSecMhvAZImMxjX1iMAEsNTgQYRDAA9Tqz1D2Sa9CgO1EHoo/KeXOejPSPYWregh7AV9GI+Vpvw7ZFHeprBcRxARbR8OZl8WqXbyMpTmgb6NHDJdFY81Deuv1lq0ChsAOwAegkqr6HwP5CDyBHDnQDuiqGPUQjUTK4/xH3WHqP8AaVDb8R0X4kQ/sDyj2zxvvMTUYG4DZF8F6OnmCfOc6YTEvrACc7eWMII99LyF4DFVPsdu/hEAIPmYsfLwhHMHykGgA7GREjaKICbNGpnc+UHfSSp9XxP9vpAocRRhJQAjFJRQEWShlqgLIPEwLQ46o8PnGCK+Iiwz6esjVMFhns1v12RDLSmTEHzhBGBEmTQwJOsIpgBYvpO59gMT/lFfuuw8iFPzJnBg6To/YXEWqOl9wHH+k2P/ACHpNeF/9EVo9cov0Zn4lemt+ZA9SJYpvpK1V+mnZnX5idKXZLNN6h56XkjYC97kkfO/0iw+MC3ujG9hoA1x93UiwPbIu18vj9DM+84wUWM5O84f9omLy4fJzd1HkvSPxCzrMZWygKDqZ5h+0XF3qpTzZsiXJ/mc6/AL6xV1LYfTi6jayAjMYlnMMkTYXMppcksefyhMS9yFHiZFmgAmg2McmDYxAImRIMUUChn2hF6o8IKqdIVNh4QAcR4ooEivFFFAC60sN1R4D5RRRjRTqStT64iiiGXjvJjaKKMATSYiigAUTZ9j/wDyh+BvpFFL4/yRNaPXae367pXfrp+JfmIop1ohmqkapuv4voYopP0ZncQ64855V7Z/+S/gn/BY8Ujl/EFs5kxxtHinMUUx1m8fpE0UUQ2RaQMUUBDGKKKAEKsLS6oiigP4TiiigIaKKKAz/9k=);
            background-size: 250px;
            background-position-x:center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:200px;
            position:center;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am1{
            color:black;
            position:center;
            text-align:center;
        }

        .amph2{
            background-image: url(https://www.targetnxt.com/wp-content/uploads/2023/01/Microsoft-SCCM-Users-Lists-809x1024.png.webp);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:200px;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am2{
            color:black;
            position:relative;
            text-align:center;
        }
        .amph3{
            background-image: url(https://bl-i.thgim.com/public/incoming/3wc5kr/article66930318.ece/alternates/LANDSCAPE_1200/Ram-pic.jpg);
            background-size: 350px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:200px;
            position:center;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am3{
            color:black;
            position:relative;
            text-align:center;
        }
        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: yellow; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="product.html" title="Products" style="color: yellow; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:yellow; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:yellow; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>People</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>Board Members</p>
                    <h4><u>Chairman</u></h4>
                    </div>
                    <div class="ceoph"></div>
                    <div class="ceo"><p align="center"><b><h2>VIKRAM K</h2></b></div>
                    <br>
                    <div class="text">
                        <p><b><u>Head executives</u></b></p><br>
                    </div>
                    <div class="manph1"></div>
                    <div class="man1"><p align="right"><b><h2>Sriram Subramanya</h2></b></p></div>
                    <div class="manph2"></div>
                    <div class="man2"><p align="left"><b><h2>Marissa Mayer</h2></b></p></div>
                    <br>
                    <div class="text"><p><b><u>Managers</u></b></p></div><br>
                    <div class="amph1"></div>
                    <div class="am1"><p align="right"><b><h2>Arun Kumar</h2></b></p></div>
                    <div class="amph2"></div>
                    <div class="am2"><p align="center"><b><h2>Priyanka</h2></b></p></div>
                    <div class="amph3"></div>
                    <div class="am3"><p align="left"><b><h2>Rampraveen Swaminathan</h2></b></p></div><br>
                    <div class="text">Thank you so much for your kind support!<br>Hope our teaching had made you more to create a new world with TECHNOLOGY.<br> We hope that, we are helping you to develop your programming skills.</div>
                </div>
                <div class="footer">
                <h3><footer style="color:black">
                Copyright &copy;2023 Developed by VIKRAM K</footer></h3></div>
            </div>
        </div>
    </body>
</html>

contact.html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Contact Us
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/style.css">
    <style>
    .text{
    
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: yellow; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="product.html" title="Products" style="color: yellow; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:yellow; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:yellow; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Contact Us</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p><b>Here are the details about us
                    <h5>Do contact us for any need</h5></b></p>
                    
                    </div>
                    <b><h2>Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                        Bangalore, Chennai, Madurai.
                    </p>
                    <ul>
                        <li><b>Landline:</b> 14345677</li>
                        <li><b>Mobile</b>: 80 60 40 2004</li>
                        <li><b>Facebook</b>: fb/Zoho Corporation</li>
                        <li><b>Email Id:</b>ZohoCorporation321@gmail.com</li>
                    </ul>
                    <div style="text-align: center;color:red;font-size:20px;"><b>Use our services and Make your bright Future!</b></div>

                </div>
                <div class="footer">
                <H3><footer style="color:black">
                Copyright &copy;2023 Developed by VIKRAM K</footer></H3></div>
            </div>
        </div>
    </body>
</html>

style.css
.home{
            height: 700px;
            width: 85%;
            border: 12px solid lawngreen;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:cyan;
        }
        .content{
            border:1px solid blue;
            background-color: white;
            width:95%;
            height:400px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .header{
            height: 128px;
            width:100%;
            background-image: url(/static/images/head.png);
            background-size: cover;
            
        }
        .logo{
            height:21%;
            width: 10%;
            position:absolute;
            background-image: url(https://cdn.iconscout.com/icon/free/png-512/free-zoho-282840.png?f=avif&w=512);
            background-size:cover;
            
        }
        .prod{
            height:auto;
            width:auto;
            position:relative;
            bottom:10px;
            left:550px;
            border:4px solid transparent;
            text-align:center;
            display: inline;
            padding:1px;
            font-family:'Algerian';
            font-size: large;  
        }
        .prod:hover{
            background-color:darkmagenta;
        }
        .people{
            height:auto;
            width:auto;
            position:relative;
            bottom:10px;
            left:700px;
            border:4px solid transparent;
            text-align:center;
            display: inline;
            padding:15px;
            font-family:'Algerian';
            font-size: large;  
        }
        .people:hover{
            background-color:darkmagenta;
        }
        .contact{
            height:20px;
            width:10%;
            position:relative;
            bottom:45px;
            left:1000px;
            border:4px solid transparent;
            text-align:center;
            padding:15px;
            font-family:'Algerian';
            font-size: large;  
        }
        .contact:hover{
            background-color:darkmagenta;
        }
                
        .h{
            height:20px;
            width:10%;
            position:relative;
            top:30px;
            left:200px;
            border:4px solid transparent;
            text-align:center;
            
            padding:15px;
            font-family:'Algerian';
            font-size: large;  
        }
        .h:hover{
            background-color:darkmagenta;
            overflow:hidden;
        }
        .footer{
            border:3px solid gold;
            width:98%;
            height:6px;
            position:relative;
            bottom: 1px;
            background-color: darkmagenta;
            text-align:center;

        }
        .title{
            border:2px solid lawngreen;
            background-color:gold;
            padding:1px;
            width:99.7%;
            height: 70px;
            text-align:center;
            font-family:'Alberian';
            margin-left:auto;
            margin-right: auto;
            
        }
        .content1{
            border:1px solid blue;
            background-color: white;
            width:98%;
            height:100px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;

        }
```

## OUTPUT:

![Output](./out31.png)
![Output](./out32.png)
![Output](./out33.png)
![Output](./out34.png)

## HTML VALIDATOR:

![HTML VALIDATOR](./valid21.png)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
