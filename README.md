# Ex04 Places Around Me
## Date: 23.11.2024

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
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="violet"><b>manaparai</b></font>    
</h1>
<h3 align="center">
<font color="blue"><b>STEFFI J (24900405)</b></font>    
</h3>
<center>
<img src="1.png" usemap="#image-map" height="610" width="1450">

<map name="image-map">
    <area target="" alt="Manaparai" title="Manaparai" href="manaparai.html" coords="896,361,114" shape="circle">
    <area target="" alt="Monfort" title="Monfort" href="monfort.html" coords="161,490,414,646" shape="rect">
    <area target="" alt="Guru" title="Guru" href="guru.html" coords="345,312,535,577" shape="rect">
    <area target="" alt="Theatre" title="Theatre" href="theatre.html" coords="1076,538,1037,667,806,661,795,546" shape="poly">
    <area target="" alt="Hotel" title="Hotel" href="hotel.html" coords="1055,118,114" shape="circle">
</map>    
</center>
</body>
</html>

manaparai.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="violet"><b>Manaparai</b></font>    
</h1>
<h3 align="center">
<font color="blue"><b>My Home Town </b></font>    
</h3>
<hr size="3" color="blue">
<p align="justify">
<front face="Georgia" size="S">
my Hometown is Manaparai 
Manapparai is a municipality in Tiruchirappalli district in the Indian state of Tamil Nadu.
Manapparai Town is located 38 km from Trichy.
Manapparai is the headquarters of the Manapparai Taluk.
Manapparai is famous for murukku (deep-fried snacks) and cattle market.
As of 2011, the town had a population of 40,510
<p>
</body>
</html>

guru.html

<html>
<head>
<title>Guru School</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="yellow"><b>guru School</b></font>    
</h1>
<h3 align="center">
<font color="cyan"><b>Guru School </b></font>    
</h3>
<hr size="3" color="cyan">
<p align="justify">
<front face="Georgia" size="S">
School name: Sri Guru matri Higher Secondary School.
It is located in manaparai block of trichy district of tamil nadu.
The school consists of grades from 1 to 12.
The school is co-educational.
This school offers the students a great place to learn and to enrich
contact number:9875643787 
<p>
</body>
</html>

hotel.html

<html>
<head>
<title>Hotel</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="green"><b>Hotel</b></font>    
</h1>
<h3 align="center">
<font color="red"><b>Hotel </b></font>    
</h3>
<hr size="3" color="red">
<p align="justify">
<front face="Georgia" size="S">
this hotel is best in both veg and non veg.
this hotel is more spacious and comfortable.
the rooms in that hotel looks luxurius like a tiny fridge having chocolates
  and large TV with king size bed for comfortable sleep at night.
contact number:6789543765 
<p>
</body>
</html>

monfort.html

<html>
<head>
<title>Monfort School</title>
</head>
<body bgcolor="blue">
<h1 align="center">
<font color="yellow"><b>Monfort School</b></font>    
</h1>
<h3 align="center">
<font color="purple"><b>Monfort School </b></font>    
</h3>
<hr size="3" color="purple">
<p align="justify">
<front face="Georgia" size="S">
School name: Monfort matri Higher Secondary School.
It is located in manaparai block of trichy district of tamil nadu.
The school consists of grades from 1 to 12.
The school is co-educational.
This school offers the students a great place to learn and to enrich
many students got state first in this school
contact number:6789543765 
<p>
</body>
</html>

theatre.html

<html>
<head>
<title>Hotel</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="green"><b>Theatre</b></font>    
</h1>
<h3 align="center">
<font color="red"><b>Theatre </b></font>    
</h3>
<hr size="3" color="red">
<p align="justify">
<front face="Georgia" size="S">
this theatre costs high eventhough it costs high it is a very perfect, comfortable and neat .
the lights in this theatre looks extrodinary
it consists of a single auditorium with rows of comfortable padded seats
it also have a concession stand for buying snacks and drinks. 
contact number:6789543765 
<p>
</body>
</html>
```

## OUTPUT

![alt text](steffi/mapapp/static/1.png)
![alt text](steffi/mapapp/static/2.png)
![alt text](steffi/mapapp/static/3.png)
![alt text](steffi/mapapp/static/4.png)
![alt text](steffi/mapapp/static/5.png)
![alt text](steffi/mapapp/static/6.png)


## RESULT
The program for implementing image maps using HTML is executed successfully.
