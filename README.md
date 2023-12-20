# Ex-06-Book-Cover-Design
Name: Niranjani.C
Reference Number :23009789

## AIM:
   Design the following book cover page using HTML and CSS

## STEPS:

     step-1  Create a folder in desktop named as book cover.
     step-2  Open the folder in VS code.
     step-3  create two files in that folder named as index.  html and index.css
     step-4  Write html code in index.html file.
     step-5  Write css code in index.css file.
     step-6  Run the code .

## HTML CODE:
 ```  
   
    <!DOCTYPE html>
<html lang="en">
    <head>
        <title>Web Development Technologies</title>
        <link rel="stylesheet" href="index.css">
    </head>
    <body>
        <section class="book">
            <br><br>
        <span id="front">EXPERT INSIGHT &nbsp;&nbsp;&nbsp;</span>
            <h1>Responsive Web Design with HTML5 and CSS</h1>
            <h4>Develop future-proof responsive websites using the latest HTML5 and CSS techniques</h4>
            <h3>Third Edition &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images (1).jpg"></h3>
            <footer>
                <div id="cover" class="outlet">
                    <span>Ben Frain</span>
                    <span id="page"><u>Packt></u></span>
                </div>
            </footer>
    </section>
    </body>
</html>
```
## CSS CODE:
```
body{
    color:rgb(255, 255, 255);
    font-family: Helvetica, sans-serif;
    background-color: #1d1c1c
}

.book{
    width: 726px;
    height:891px;
    background-color:rgb(0, 0, 0);
    margin:auto;
    position: relative;
    background-image: url(images.jpg);

    background-repeat: no-repeat;
    background-size:606px;
    background-position: bottom 150px center;
}
h1{
    font-size:70px;
    margin:50px;
    margin-bottom:0px;
}
h3{
    margin:0px 0px 90px 60px;
    position: absolute;
    bottom:0px;
    font-size: x-large;
    color: #f47027;
    
}


h4{
    font-size:20px;
    margin:60px;
   margin-top:10px;
   width:430px;
}
#front{
    border-bottom:2px solid #f47027;
    padding:100px 0px 5px 30px;
}
footer{
    position: absolute;
    bottom: 0px;
    border-top:2px solid #f47027;
    padding-top:10px;
    width:726px;
}
#cover {
    display: flex;
    justify-content: space-between;
}
  #cover span{
    margin:10px 0px 20px 60px;
    font-size: xx-large;
    font-weight: bold;
  }
  #page{
    padding-right:60px;
  }
```
## OUTPUT:
![Alt text](image.png)

## RESULT:
    Thus the program created successfully.
