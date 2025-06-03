# Ex.06 Book Front Cover Page Design
## Date: 13-05-2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
Developed By: Dhanvant Kumar V                                                                                                                                                          
Reg No: 212224040070
### book.html
```html
<!DOCTYPE html>
<html>
<head>
    <title>Book Cover</title>
    <link rel="stylesheet" href="book.css">
</head>
<body>
    <div class="container">
    <div class="cover">
        <div class="expert">EXPERT INSIGHT</div>
        <h1><span class="highlight">Extensive Guide on Andriod Development using Flutter</span></h1>
        <p class="subtitle">Accelerate your Android Development with Flutter covering the advanced topics</p>
        <p class="edition">First Edition</p>
        <div class="wave"></div>
        <div class="space"></div>
        <div class="bottom">
            <span class="author">Dhanvant Kumar V</span>
            <span class="publisher">Saveetha<br>Publications</span>

        </div>
    </div>
</div>
</body>
</html>

```
### book.css
```css
body {
    top:50%;
    left:50%;
    font-family: Arial, sans-serif;
    background: black;
}

.cover {
    width: 400px;
    height: 600px;
    position: relative;
    background: url('hellom.webp') ;
    background-size: cover;
    border-radius: 15px;
    box-shadow: 0 0px 20px rgb(96, 219, 102);
    overflow: hidden;
    color: black;
    text-align: left;
    padding: 20px;
}

.container{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
    box-sizing:border-box;
}

.expert {
    color: black;
    font-size: 15px;
    border-top: 3px solid rgb(108, 31, 3);
    padding-top: 5px;
    margin-bottom: 20px;
}

h1 {
    font-size: 32px;
    margin: 0;
    font-weight: 800;
    line-height: 1.3;
}

.highlight {
    color: black;
    font-weight:800;
}

.subtitle {
    color: rgb(9, 82, 12);
    margin-top: 15px;
    font-size: 16px;
    font-weight: 750;
}

.edition {
    color: rgb(171, 43, 43);
    font-weight: bold;
    font-size: 20px;
    margin-top: 30px;
}

.wave {
    height: 40px;
    /* background: linear-gradient(90deg, #66ccff, #99ffcc, #ccff99); */
    opacity: 0.6;
    margin: 30px 0;
    border-radius: 50% 50% 0 0;
}

.space {
    height: 100px;
    width: 100px;
    opacity: 1;
    margin: 30px 0;
    border-radius: 50% 50% 50% 50%;
    margin-left:auto;
    background-image: url('www.png');
    background-size:cover;
}

.bottom {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 40px;
    border-top: 2px solid #444;
    padding-top: 20px;
}

.author {
    font-weight: 300;
    font-size: 15px;
}

.publisher {
    font-size: 15px;
    font-weight: 400;
    color: black;
}

```

## OUTPUT:
![alt text](<Screenshot (178).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
