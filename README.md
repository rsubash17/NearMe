# Ex04 Places Around Me
## Date: 2-04-2024 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html
<html>
   <head>
   <title>MY CITY</title>
   </head>
   <body>
   <h1 align="center">
   <font color="black"><b>Thoothukudi</b></font>
   </h1>
   <h3 align="center">
   <font color="green"><b>SUBASH.R(212223230218)</b></font>
   </h3>
   <center>
      <img src="thooth.png" usemap="#image-map">

      <map name="image-map">
          <area target="" alt="Kamaraj College" title="Kamaraj College" href="college.html" coords="1147,827,1310,895" shape="rect">
          <area target="" alt="GRT Jewellers" title="GRT Jewellers" href="jewellers.html" coords="1256,342,1407,391" shape="rect">
          <area target="" alt="Poorvika " title="Poorvika " href="mobile.html" coords="695,568,859,617" shape="rect">
          <area target="" alt="Specs" title="Specs" href="shop.html" coords="1179,444,1354,493" shape="rect">
          <area target="" alt="SRM Hotel" title="SRM Hotel" href="hotel.html" coords="1759,690,1896,748" shape="rect">
      </map></center>
   </body>
   </html>
hotel.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="silver"><b>THOOTHUKUDI</b></font>
</h1>
<h3 align="center">
<font color="red"><b>SRM Hotel Tuticorin</b></font>
</h3>
<hr size="3" color="green">
<p align="justify">
<font face="Georgia" size="6">
  It is located in Thoothukudi,Thoothukudidistrict. At Beach Road Near Old State bank office.
   Opposite to Roche park.
   </font>
</p>
</body>
</html>

college.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="blue">
<h1 align="center">
<font color="white"><b>Thoothukudi</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>Kamraj College</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="6">
It is located near Post olffice,thirucendur Main Rd; 
 Opposite To Taluk Office Thoothukudi district.
It is popular for culturals. It is Arts College.
</font>
</p>
</body>
</html>

mobiles.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="brown"><b>THOOTHUKUDI</b></font>
</h1>
<h3 align="center">
<font color="yellow"><b>Poorvika Mobiles Thoothukudi</b></font>
</h3>
<hr size="4" color="black">
<p align="justify">
<font face="Georgia" size="6">
    Poorvika sells a wide category of devices in its showrooms and Online portal.
   It is located at Madurai Main Rd, near Bus Stand,in ,Thoothukudi, Tamil Nadu
</font>
</p>
</body>
</html>

shop.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="white"><b>THOOTHUKUDI</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>specsmakers</b></font>
</h3>
<hr size="4" color="white">
<p align="justify">
<font face="Georgia" size="6">
    The shop in Shanmugapuram, Thoothukudi offers a wide range of services related to specs.It is located shanmugapuram at thoothukudi distict.
</font>
</p>
</body>
</html>

jewellers.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="blue"><b>THOOTHUKUDI</b></font>
</h1>
<h3 align="center">
<font color="grey"><b>GRT Jewellers</b></font>
</h3>
<hr size="3" color="pink">
<p align="justify">
<font face="Georgia" size="6">
       GRT is situated southwest of Granite quarry, and northwest of Government Hospital,at main road,thoothukudi district.
    </font>
</p>
</body>
</html>
```

## OUTPUT
![thooth](https://github.com/rsubash17/NearMe/assets/147139828/adcd41de-58c5-46b4-bfe9-e336294a2964)
![subgrt](https://github.com/rsubash17/NearMe/assets/147139828/ee6597ca-71bc-4d3f-9aa4-08f110836028)
![subspec](https://github.com/rsubash17/NearMe/assets/147139828/f71b42be-0dc9-4b55-ac35-3f3ca2c05809)
![submobi;e](https://github.com/rsubash17/NearMe/assets/147139828/0c7c218b-524f-4cd8-a1ed-74d420272627)
![subcollege](https://github.com/rsubash17/NearMe/assets/147139828/f7677c61-f7f1-4272-860f-cffe7f1b478f)
![subhotel](https://github.com/rsubash17/NearMe/assets/147139828/28c92c4e-dc45-494d-92d8-52fe7a4fa15f)






## RESULT
The program for implementing image maps using HTML is executed successfully.
