# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

##Design Steps:

### Step 1:
clone the github resporistry and create adjango admin interface.
### Step 2:
write HTML and CSS for book cover page and execute it
and
validate the HTML and CSS code
## Code:
HTML CODE.

<!DOCTYPE html>
{% load static %}
<html lang="en">

<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>coverpage</title>
   <link rel="stylesheet" href="static/css/cover.css">
   <style>
   main{
   background-color: rgb(58, 54, 54);
   background-image: url('static/images/book.png');
   height: 1000px;
   width:800px;
   margin-left: 500px;
}
   </style>
</head>
<body>
   <main>
       <h4>EXPERT INSIGHT</h4>
       <hr id="start" color="orange">
       <h1>
           Responsive Web <br>
           Design with <br>
           HTML5 and CSS
       </h1>
       <p>Develop future-proof responsive websites <br>
       using the latest HTML5 and CSS techniques</p>

       
       <p id="edision">THIRD EDISION</p>
       <hr id="aj" color="orange">
       <img src="static/images/ben.png" alt="sdfgh">
       
          <p id="author">Ben Frain</p>
           <p id="packt"> <u> Packt> </u></p>
   
   
   </main>
  
</body>
</html>>

## Output:

![Screenshot 2023-12-30 104118](https://github.com/H515piyush/cover-page-design/assets/147472999/66d409ac-0138-435a-83e5-d16d29b22c3e)


## Result:
The cover page is created
