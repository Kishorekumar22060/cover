# Ex.06 Book Front Cover Page Design
## Date:

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
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport" 
        content="width=device-width, initial-scale=1.0">
        <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }

        .bookpage {
            width: 500px;
            height: 600px;
            color: rgb(78, 100, 210);
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(thunder.jpg);
            background-size: cover;
        }
        .insight{
            color: rgb(101, 116, 230);
        }
        .hrstyle{
            width:100px;
        }
        .author{
            display: inline;
            position: relative;
            color: rgb(82, 96, 208);
            top:190px;
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: 19px;
            text-align: center;
            position: relative;
            top: 30px;
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color: rgb(8, 12, 37);
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
        }
        .mypic{
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
            <div class="insight">EXPERT INSIGHT</div>
            <div class="hrstyle"><hr style="color: rgb(104, 121, 229);"></div>
            <div class="booktitle"><h1>MATHEMATICS AND LOGICS</h1></div>
            <div class="subtitle">RELATIVITY OF LOGICS</div>
            <div class="mypic"><img src="mine.png" width="130" height="145" alt=""></div>
            <div class="id"><hr style="color: rgb(104, 121, 229);"></div>
            <div class="author"><p><b>BY Kishore Kumar U</b></p></div>
            <div class="pub">OPEN >>></div>
            <div class="ed"><b>Special Edition</b></div>
        </div>
    </bodY>
</html>
```


## OUTPUT:
![image](https://github.com/Kishorekumar22060/cover/assets/141472136/079594ea-f287-4b61-b550-0cea18371b2c)
![image](https://github.com/Kishorekumar22060/cover/assets/141472136/15516e12-1ccf-4af1-9efc-39d6b3a7ae61)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
