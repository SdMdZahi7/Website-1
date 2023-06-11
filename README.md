# Website-1
## AIM:
To create a portfolio using HTML and CSS

## ALGORITHM:
Set up the basic structure of your HTML document.

Create a CSS file named "styles.css" and link it to your HTML document. This file will contain the CSS rules for styling your portfolio.

Design the layout of your portfolio using HTML elements such as < header >, < nav >, < section >, < article >, and < footer >. Use appropriate classes or IDs to style these elements later with CSS.

Add a header section to display your name or the title of your portfolio.

Add images or media to enhance your portfolio. You can use the  tag to display images and embed videos or other media using appropriate HTML tags.

Apply responsive design techniques to ensure your portfolio looks good on different devices and screen sizes. Use CSS media queries to adjust the layout and styling as needed.

Apply CSS styling to your portfolio elements by targeting their respective classes or IDs in the "styles.css" file. Customize the colors, fonts, spacing, and other visual properties to match your desired design.

# CODE:
## HTML CODE:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Cafe Kaelish</title>
    <link rel="stylesheet" href="stylesheet.css">
    <link href='https://fonts.googleapis.com/css?family=Alegreya' rel='stylesheet'>
    <link href='https://fonts.googleapis.com/css?family=Alegreya Sans SC' rel='stylesheet'>
    <link href='https://fonts.googleapis.com/css?family=Gruppo' rel='stylesheet'>
</head>
<body>
    <div class="container">
    <div class="wallpaper">
        <img src="bg3.jpg" id="banner" style="height: 100%; width: 100%;">
        <img src="logo.png" class="mid logo" style="height: 150px; width: 150px;">
        <h2 class=" mid title">Famous for its Rarity, Perfect Flavour.</h2>
        <h3 class="mid aroma">Intense Aroma & Balanced Taste</h3>
        <img src="cof2.png" class="mid coffee" style="height: 250px; width: 250px;">
        <p class="mid roast">DARK ROAST</p>
        <p class="mid roastinfo">Duls aute irure dolor in <br>&emsp;&emsp;reprehenderit <br> in volupt ate vellt essets</p>
        <img src="lattefin.png" class="mid latte" style="height: 300px; width: 350px;">
        <p class="mid cup">Exceeding the Standard<p class="mid whitecup">as the</p></p>
        <p class="mid whitecup1"> Best Coffee in the World</p>
        <p class="mid est">Est. 1993</p>
        <p class="mid desc">In the majestic Blue Mountains of Jamaica grows the <br>world's finest coffee. At elevations higher than 2000 ft <br>above sea level, the rich soil and continuous rainfall<br> combine to create conditions perfect for cultivating<br> the world's most distinguished brew, Kaelish Coffee.</p>
        <button class="mid history">OUR HISTORY</button>
        <p class="mid info">Kaelish Coffee company exceeds the standard in what is already known <br>as the best coffee in the world.</p>
        <p class="mid info1">" Jamaican Blue Mountain Coffee "</p>
        <button class="mid products">BROWSE OUR PRODUCTS</button>
        <img src="cof2.png" class="mid finalprod" style="height: 300px; width: 300px;">
        
    </div>
    </div>
</body>
</html>
~~~
## CSS CODE:
~~~
body{
    margin: 0;
}
.container{
    width: 850px;
    margin-left: auto;
    margin-right: auto;
}

.wallpaper{
    background: rgb(0, 0, 0);
    overflow: hidden;
}

#banner {
   object-fit: cover;
   opacity: 0.2;
}

.mid{
    position: absolute;
    top: 11%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.logo{
    opacity: 0.7;
}

.title{
    color: #d1cece;
    font-family: Georgia, 'Times New Roman', Times, serif;
    font-weight: lighter;
    margin-top: 8%;
}

.aroma{
    color: #d1cece;
    font-family: 'Alegreya Sans SC';
    font-weight: lighter;
    margin-top: 10%;
}

.coffee{
    margin-top: 23%;
}
.roast{
    font-family: 'Alegreya Sans SC';
    color: #d3b134;
    top: 335px;
    left: 570px;
    font-size: 20px;
    opacity: 0.7;
}

.roastinfo{
    font-family: 'Alegreya';
    color: #d1cece;
    top: 385px;
    left: 575px;
    font-size: 15px;
}

.latte{
    opacity: 0.7;
    top: 770px;
    left: 520px;
}

.cup{
    font-family: Georgia, 'Times New Roman', Times, serif;
    color: #d3b134;
    top: 650px;
    left: 850px;
    font-size: 22px;
    font-weight: lighter;
    opacity: 0.7;
}

.whitecup{
    font-family: Georgia, 'Times New Roman', Times, serif;
    color: #f2f0f0;
    top: 653px;
    left: 1000px;
    font-size: 20px;
    font-weight: lighter;
}

.whitecup1{
    font-family: Georgia, 'Times New Roman', Times, serif;
    color: #f2f0f0;
    top: 685px;
    left: 843px;
    font-size: 20px;
    font-weight: lighter;
}

.est{
    font-family: 'Alegreya';
    color: #d3b134;
    top: 720px;
    left: 763px;
    font-size: 15px;
    opacity: 0.7;
}

.desc{
    font-family: 'Gruppo';
    color: #d1cece;
    top: 780px;
    left: 930px;
    text-align: justify;
}

.history{
    top: 122%;
    left: 783px;
    padding: 15px;
    padding: 10px;
    font-size: 13px;
    background-color:transparent;
    color: #d1cece;
    border: 1px solid #d1cece;
    font-family: 'Alegreya Sans SC';
    cursor: pointer;
}

.history:hover{
    background-color: #a49356;
}

.info{
    text-align: center;
    color: #d1cece;
    font-family: 'Alegreya';
    top: 1000px;
    font-size:larger ;
}

.info1{
    text-align: center;
    color: #d3b134;
    opacity: 0.9;
    font-family: 'Alegreya Sans SC';
    top: 1045px;
    font-size:larger ;
}

.products{
    top: 155%;
    left: 755px;
    padding: 15px;
    padding: 10px;
    font-size: 13px;
    background-color:#a49356;
    color: #d1cece;
    border: 1px solid #d1cece;
    font-family: 'Alegreya Sans SC';
    cursor: pointer;
}

.products:hover{
    background-color: transparent;
}

.finalprod{
    margin-top: 85%;
}

.footer{
    display: block;
    width: 100%;
    /* height: 25px; */
    background-color: #4d4c4b;
    text-align: center;

  }
~~~
## OUTPUT:
![image](https://github.com/SdMdZahi7/Website-1/assets/94187572/74befb0a-d629-4749-acef-cadbdd0779cc)
![image](https://github.com/SdMdZahi7/Website-1/assets/94187572/73a502f0-5051-4c64-a7e1-11708f474bd0)


## RESULT:
Thus, a Portfolio is created using HTML and CSS.
