# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Create a new folder and clone the Github repository.

### Step 2:
Start a django project interface.

### Step 3:
Create a static folder and its sub directories(Images,html).

### Step 4:
Write the html code in the html folder and upload the images in the images folder.

### Step 5:
Run the server.
## Code:
```html
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/BG1.jpg);
            background-size: cover;
        }
            

        .toptext{
            color:yellowgreen;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: red;
            display: inline;
            position: relative;
            color:red;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .edition{
            color:yellowgreen;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
            left: 70px;
        }
        .subtitle1{
            font-family: Tahoma;
            font-size: large;
            position: relative;
            top: 30px;
            left: 140px;

        }
        .photo{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="tophr">
                <hr style="color:yellow;">
            </div>
            <div class="booktitle">
                <h1>Cloud Computing</h1></div>
            <div class="subtitle">
                <h3>Concepts,Technology and</h3>
            </div>
            <div class="subtitle1">
                <h3>Architecture</h3>
            </div>
            <div class="photo">
                <img src="/static/images/PIC1.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color:orange;">
            </div>
            <div class="author">
               <p><b>Ragul R</b></p>
            </div>
            <div class="publisher">
                
            </div>
            <div class="edition">
                <b>First Edition</b>
            </div>
            
        </div>
    </body>
</html>
```
## Output:
![Output](https://github.com/RagulRM/cover-page-design/assets/121609342/325fac08-dac3-4356-af1b-4ac24b00a9d4)
## Result:
A website to display the cover page design of a book was developed and displayed successfully.
