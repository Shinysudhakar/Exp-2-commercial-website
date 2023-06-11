# EXP 02 - CREATING A COMMERCIAL WEBSITE USING HTML & CSS
## AIM:
To create a commercial website using html and css.

## SOFTWARE:
Visual Studio Code.

## ALGORITHM:
1) Create a new HTML file and save it with a .html extension.Begin with the basic structure by adding the <!DOCTYPE html> declaration at the top.
2) Set up the Head:

       Inside the <head> element, add the <title> element and give it a meaningful title for your website.
       Link your CSS file by adding the <link> element with the rel attribute set to "stylesheet" and 
       the href attribute pointing to your CSS file.

3) Develop the Content:

        Divide the main content area into sections using appropriate HTML elements like <section>, <div>, or <article>.
        Use headings <h1> to <h6> to structure your content hierarchically.
        Incorporate text, images, videos, and other media within the content sectionS


4) Style with CSS:
 
  Create a new CSS file and save it with a .css extension.
  Select the elements you want to style using CSS selectors.
  Apply styles using properties and values. 
  For example, you can change colors, fonts, sizes, margins, and padding.

5) Find a web hosting provider to host your website online.
Upload your HTML, CSS, and any other necessary files to the hosting server.

6) Test your website again after deployment to ensure it works as intended.
  
## PROGRAM:
  
### HTML CODE:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>webpage</title>
    <link rel="stylesheet" href="style.css"/>
</head>
<body>
    <div class="container">
        <div id="header">
            <div style="color:red">BEST TUNING</div>
            <div><a href="#">Home</a></div>
            <div><a href="#">Project</a></div>
            <div><a href="#">Team</a></div>
            <div><a href="#">Contact</a></div>
            <div><button style="background-color: red;padding:8px;border-radius: 15px;"><a href="#">Book An Appointment</a></button>
        </div>
        
        
    </div>
    <center><img src="https://www.bugatti.com/fileadmin/_processed_/sei/p329/se-image-87f40fb0b7981f56cc3f3c7f4dd788c2.jpg" height="500px" width="1000px;"></center>
    <div class="img">
        <p><b><i>TUNING PERFECTION</i></b></p>
        <p >Tuning in an upgrade that unlocks hidden<br/>potential of your car</p>
        <p><a href="#">Explore more</a></p>
    </div>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSlc15nekMv9jxyCeKx3iYNkwie5PuJyHIEnqLmlwXoS623N3OJxVgF4GPlIT0wjEapUCc&usqp=CAU" style="float:right;padding-left: 120px;">
    <div>
        <p style="color:white;padding-top: 50px;font-size: 25px;"><b>WHY DO YOU WANT IT?</b></p>
        <p style="color:white;font-size:60px">WHAT IS TUNING AND <br/>WHY DO YOU WANT IT?</p>
        <p style="text-align: justify;color:white;font-size:25px">Tuning is an upgrade to the software in the vehicle's computer.Custom software is installed that charges many parameters
        that control the way the engine operators. With proper tuning you can increase both power and fuel of economy.</p>
    </div>
    
    <div style="display:flex;color:white">
        <div style="padding-right: 30px;"><p>A comprehensive tool<br/>for high horsepower<br/>builds.</p></div>
        <div><p>With proper tuning,<br/>you can increase fuel<br/>economy.</p></div>
    </div>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTbAO2GUFuRSeWPvWBbORezFtMijYhahLPrDcj9rbcstw7i50b2fKnjdlU8EhGCvJO9ZvU&usqp=CAU" height="500px" width="700px" style="float: left;padding-right:50px;">
    <div style="color:white;font-size: 20px;margin-bottom:100px;">
        <h3 ><b>ADVANTAGES</b></h3>
        <p style="font-size:50px">WHATCAN I EXPECT FROM TUNING?</p>
        <p style="text-align: justify;">What can I expect from Tuning?<br/>Through proper modification, it is possible to greatle increase the power output of the vehicle, while 
            at the same time omproving safety and longevity of the engine,drivability, and smoothness.
        </p>
        <div style="display: flex;">
            <h3 style="padding-right: 300px;">20-35 hp</h3>
            <h3>35-50 hp</h3>
        </div>
        <div style="display: flex;">7
            <h4 style="padding-right: 200px;">Roughly increase from <br/>a stage 1 tune</h4>
            <h4 >Roughly increase from <br/>a stage 2 tune</h4>
        </div>
    </div>
    
</body>
</html>


    

### CSS CODE:
```      body{
    background-color: black;
   margin:50px;
}

header
{
    display:flex;
    justify-content:space-around;
}
a{
    color:white;
    
}
.img
{
    font-size:20px;
    color:white;
}
footer
{
   display: flex;
   justify-content:space-around;
}


## OUTPUT


![1686480659895](https://github.com/Shinysudhakar/Exp-2-commercial-website/assets/127575325/8c7fab66-bf9d-44d0-995a-84facc79f9a2)







## RESULT:
      
Thus the website is created.
