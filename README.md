<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css" type="text/css">
</head>
<body>
    <header>
       <div class="header">
         <h1>KOPIKO USA</h1>
        <p>World’s #1 Coffee Candy & Coffee Mix</p>
        
       </div>

       
    </header>
    <div class="fluid">
        <div class="container">
            <ul class="options">
                <li>HOME</li>
                <li>COLLECTION</li>
                <li>SHOP</li>
                <li>NEWS&UPDATES</li>
                <li>ABOUT US</li>
                <li>CONTACT US</li>
            </ul>
        </div>
    </div>
    
        <div class="container">
            <h1 class="candy">Candy</h1>
        </div>
        <div class="image">
            <img class="img" src="Screenshot-2024-02-07-151701.webp" alt="">
        </div>
        <div class="p-head">
            <h1>Your Pocket Coffee, Anytime Anywhere !</h1>
            <p><strong>Kopiko Coffee Candy</strong> is the World’s #1 selling coffee candy, made from the finest coffee beans, specially blended to give you enjoyment of <br> real coffee without having to brew. It’s like having a cup of coffee wherever you go.</p>
            <p>Our bite sized, individually wrapped candies are available in regular Coffee and Cappuccino flavors. We have many packaging options for you <br> to choose from contact us for more information or visit our site.</p>
        </div>
        <div class="row">
            <div class="col1">
                <img src="13315476_1733027933606198_7623408530663400473_na2-.webp" alt="">
            </div>
            <div class="col1">
                <img src="a705e3f3e5e790a55c9a7311dcf3e4b3_h300_i5_0x0.webp" alt="">
            </div>
            
        </div>
        <div class="line">
            <p>Real coffee candy made with the finest Java Coffee Beans for a rich taste sensation.</p>
        </div>
        <div class="para">
            <p>Kopiko Coffee candies are tantalizingly tasty sweets with the sublime flavor and rich aroma that only comes from real coffee beans grown <br> on the island of Java. Java’s fertile, volcanic soil and tropical climate combine to create ideal conditions for growing the best coffee in the <br> world. Quality is preserved by traditional farming methods and the finest beans are handpicked to ensure their freshness. These delicious <br> beans are used to create Kopiko candy and there is no mistaking that real coffee taste. Kopiko Coffee candies are enjoyed in over 80 <br> countries worldwide for a genuine coffee taste sensation anytime, anywhere.</p>
        </div>
        <div class="para1">
            <p>Kopiko is the essence of the highest quality coffee. A single Kopiko candy contains real extract from real coffee beans. A real coffee <br> pleasure anytime you want. Taste it, coffee inside!</p>
        </div>
        <div class="row1">
            <div class="col2">
                <img src="3D-S2062057633-KOPIKO-CAPPUCINO-JAR-800G-USA.webp" alt="">
                <img src="small-KOPIKO-COFFEE-CANDY-12-x-120-G-GB-USA.webp" alt="">
                <img src="small-KOPIKO-COFFEE-CANDY-12-x-120-G-GB-USA.webp" alt="">
            </div>
            
        </div>
        <div class="last">
            <p>Copyright © 2025 KOPIKO USA | Signify Dark by WEN Themes</p>
        </div>
        
                    
</body>
</html>

CSS

body{
    margin: 0;
    padding: 0;
    background-color: black;
}
.fluid{
    width: 100%;
    height: 45vh;
    display: grid;
    background-color: black;
}
.container{
    width: 80%;
    margin: 0 auto;
}
.header{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    width: 90%;
    height: 20vh;
    display: flex;  
    background-color: black;
    line-height: 1px;
    font-family: "Playfair Display", serif;  
    column-gap: 2px;
   border-bottom: 1px solid gray;
   left: 20px;
   position: absolute;
       left: 50px;
    
}
.header h1{ 
    color: gray;
    cursor: pointer;

}
.header p{
    color: gray ;
    font-family: Arial, Helvetica, sans-serif;
    font-size: small;
    letter-spacing: 4px;
}
.options{
    text-decoration: none;
    position: absolute;
    left: 20px;
    color: #fff;
    gap: 10px;
    display: flex;
    list-style: none;
    padding-left: 175px;
    font-size: 8px;
    padding-top: 70px;
    letter-spacing: 2px;
}
.candy{
    color:#fff ;
    padding-left: 285px;
    font-size: 20px;
    margin: 0;
    margin-bottom: 35px;

}
.image{
   
    
    width: 58%;
    height: 201px;
    align-items: center;
    position: relative;
    left: 173px;
   
}
.img{
    object-fit: cover;
    width: 100%;
    height: 100%;
}
.p-head{
   width: 100%;
   height: 40px;
  text-align: center;
   position: relative;

}
.p-head h1{
    color: #fff;
    font-size: 15px;
    font-family: Arial, Helvetica, sans-serif;
}
.p-head p{
    text-align: start;
    color: gray;
    font-size: 8px;
    padding-left: 145px;
    font-family: Arial, Helvetica, sans-serif;
    position: relative;
}
.row {
  width: 70%;
  display: flex;
  justify-content: center;
  gap: 20px; 
  padding-top: 55px;
  padding-left: 130px;
}
.col1 img {
  width: 100%; 
  height: 140px; 
  object-fit: cover; 
  
}
.col1{
    flex: 1; 
  max-width: 400px; 
}
.line{
    color: gray;
    padding-left: 125px;
    font-size: 9px;
    font-family: Arial, Helvetica, sans-serif;
}
.para{
     color: gray;
    padding-left: 125px;
    font-size: 9px;
    font-family: Arial, Helvetica, sans-serif;
}
.para1{
    color: gray;
    padding-left: 125px;
    font-size: 9px;
    font-family: Arial, Helvetica, sans-serif;
}
.row1{
    width: 90%;
    display: flex;
    justify-content: center;
    gap: 10px;
    padding-top: 30px;
}
.col2 img{
        width: 32%;
    height: 150px;; 
   
  
}
.col2{
     flex: 1; 
  max-width: 400px; 
  padding-left: 95px;
}
.last{
    text-align: center;
    color: #97978b;
    font-size: 7px;
    padding-top: 55px;
    margin: 25px;
}
