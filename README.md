# Ex04 Places Around Me
# Date:24/09/2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html

<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>mannargudi</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>kaviraj(25017431)</b></font>
</h3>
<center>
<img src="img_map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700,250,850,400" href="temple.html" title="My Home Town">
<area shape="rect" coords="570,230,45" href="park.html" title="My Home Town">
<area shape="rect" coords="640,200,30" href="town.html" title="My Home Town">
</map>
</center>
</body>
</html>

temple.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>mannargudi</b></font>
</h1>
<h3 align="center">
<p align="justify">
<font color="blue"><b>big temple - The Tourists Attraction</b></font>
</p>
</h3>
<p align="justify">
<hr size="3" color="red">
<font face="mannai" size="5">
Mannargudi is a beautiful and historic town located in the Tiruvarur district of Tamil Nadu, India. It is famously known as the "Temple Town" because of its rich spiritual heritage. The town’s pride is the Rajagopalaswamy Temple, a massive and ancient Vaishnavite temple dedicated to Lord Krishna (Rajagopalaswamy). This temple attracts thousands of devotees every year, especially during festivals like Panguni Thiruvizha.
Mannargudi is surrounded by lush green paddy fields, coconut groves, and small water canals, making it a peaceful and scenic place. Agriculture is the main occupation here, and the town is well-known for its rice cultivation.
Culturally, Mannargudi has a deep connection with Carnatic music, Bharatanatyam dance, and Tamil traditions. The people are warm and friendly, and the town maintains a mix of tradition and simple modern lifestyle.
It is also well-connected by road and rail, making it easy to travel to nearby towns like Thiruvarur, Thanjavur, and Kumbakonam.
</font>
</p>
</body>
</html>


park.html

<html>
<head>
<title>parks</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="aqua"><b>mannargudi</b></font>
</h1>
<h3 align="center">
<p align="justify">
<font color="black"><b>PARK</b></font>
</p>
</h3>
<p align="justify">
<hr size="3" color="white">
<font face="mannai" size="5">
Mannargudi has a beautiful public park that is a favorite spot for families and children. The park has well-maintained walking paths, green lawns, and shady trees, making it a peaceful place for morning and evening walks. 
There are play areas for kids with swings, slides, and benches for visitors to relax.
Many people visit the park for jogging, yoga, and spending time with friends in the fresh air. 
During weekends and evenings, the park becomes lively with families and children enjoying the open space. 
It is one of the best places in the town for relaxation and recreation.
</font>
</p>
</body>
</html>


town.html

<html>
<head>
<title>Town</title>
</head>
<body bgcolor="hotpink">
<h1 align="center">
<font color="black"><b>mannargudi</b></font>
</h1>
<h3 align="center">
<p align="justify">
<font color="black"><b>TOWNS AND STORES</b></font>
</p>
</h3>
<p align="justify">
<hr size="3" color="black">
<font face="mannai" size="5">
Mannargudi has a lively town area with busy streets full of shops and small businesses. 
You can find vegetable markets, grocery stores, textile shops, jewelry stores, and traditional sweet stalls. 
There are also modern stores and supermarkets where people shop for daily needs. 
The town area is always active, especially in the mornings and evenings, when people come to buy fresh vegetables and other goods.
Mannargudi’s main streets are well-known for their festival decorations, especially during temple festivals, when the entire town lights up with colors and crowds. 
It gives a perfect mix of traditional and modern lifestyle.
</font>
</p>
</body>
</html>
```
# OUTPUT
<img width="1362" height="680" alt="1" src="https://github.com/user-attachments/assets/ae7a7739-fbd3-4006-882d-0b6fa2c5d2f2" />
<img width="1031" height="603" alt="2" src="https://github.com/user-attachments/assets/0449ba9d-ad18-487a-a294-0e6893905e36" />
<img width="1034" height="606" alt="3" src="https://github.com/user-attachments/assets/26529f8a-b780-4e44-bb98-0632a6116585" />
<img width="1036" height="600" alt="4" src="https://github.com/user-attachments/assets/259c1c4a-5545-4511-a61a-383e475eac00" />
# RESULT
The program for implementing image maps using HTML is executed successfully.
