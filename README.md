# Ex.06 Book Front Cover Page Design
## Register Number: 212221040044
## Date: 28-10-2023

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
### Bookcover.html:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial scale=1.0">
        <meta name="Book Cover">
        <title>BOOK COVER</title>
        <link rel="icon" href="book.png">
        <link rel="stylesheet" href="bookcover.css" type="text/css">
    </head>
    <body>
        <div class="top">
            <h1>WEB DESIGN</h1>
        </div>
        <div class="middle">
            
            <img src="image.jpg" alt="Main picture" height="200px" width="746px">
           
        </div>
        <div class="bottom">
            <h1>PLAYGROUND</h1>
            <div class="box1">
                <h2>HTML + CSS</h2>
            </div>
            <div class="box2">
                <h2>THE INTERACTIVE WAY</h2>
            </div>
            <div class="author">
                <h2>Sherin Joys Catherina</h2>
            </div>
        </div>
    </body>
</html>
```

### Bookcover.css:
```
body{
    background-color: black;
    overflow-x: hidden;
}
.top{
    height: 150px;
    width: 750px;
    background-color: #ffba42;
    overflow-y: hidden;
    margin-left: auto;
    margin-right: auto;
}
.middle{
    height: 200px;
    width:100%;
    overflow-y: hidden;
    margin-left: 375px;
    border: none;
    box-shadow: inset 0 0 7px #000000;
}
.middle img{
    margin-left: 7px;
}
.bottom{
    height: 375px;
    width: 750px;
    background-color:#00537a;
    overflow-y: hidden;
    margin-left: auto;
    margin-right: auto;
}
h1{
    text-align: center;
    font-size: 80px;
    font-family:Georgia, 'Times New Roman', Times, serif
}
.bottom h1{
    margin-top: -3px;
}
.top h1{
    margin-top: 65px;
}
.box1{
    border-bottom: 40px solid #ffba42; 
    border-left: 20px solid transparent;
    transform: rotate(180deg); 
    width: 390px;
}
.box1 h2{
    position: absolute;
    transform: rotate(180deg);
    margin-left: 15px;
    margin-top: 1px;
    text-align: right;
}
.box2{
    border-bottom: 40px solid #318a98;  
    border-right: 20px solid transparent; 
    transform: rotate(180deg);
    width: 525px;
    margin-left: 205px;
    margin-top: 30px;
}
.box2 h2{
    position: absolute;
    transform: rotate(180deg);
    margin-left: 165px;
    margin-top: 1px;
    text-align: right;
}
.author h2{
    margin-top: 40px;
    text-align: center;
    text-decoration: underline;
}
```


## OUTPUT:
<img width="551" alt="Screenshot 2023-11-17 142846" src="https://github.com/divvisha/cover/assets/127508123/e7618e61-ce8c-4005-a321-dba15e74a3f9">


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
