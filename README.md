# Ex04 Places Around Me

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
            <font color="red"><b>Salem</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Srimathi S</b></font>
        </h3>
        <center>
            <img src="Map.png" usemap="#MyCity" height="610" width="1450">
            <map name="#MyCity">
                <area shape="rect" coords="775,353,1044,490" href="home.html" title="My Home Town">
                <area shape="circle" coords="1445,94,1688,251" href="tumbal.html" title="Tumbal">
                <area shape="circle" coords="1121,502,1364,659" href="tirumanur.html" title="tirumanur">
                <area shape="circle" coords="396,18,639,175" href="mecheri.html" title="mecheri">
                <area shape="rect" coords="35,452,278,609" href="hill.html" title="Hill Station">
            </map>
        </center>
    </body>
</html>

home.html

<!DOCTYPE html>
<html>
<head>
  <title>My Home Town</title>
</head>
<body bgcolor="cyan">
  <h1 align="center">
    <font color="red"><b>Salem</b></font>
  </h1>
  <h3 align="center">
    <font color="blue"><b>Salem - My Home Town</b></font>
  </h3>
  <hr size="3" color="red">
  <p align="justify">
    <font face="Georgia" size="5">
        Salem is a vibrant city in the Indian state of Tamil Nadu, nestled in the Salem district at the foothills of the Shevaroy and Kolli Hills. Known as the “Steel City” for its long history of steel production and as the “Mango City” for its celebrated, sweet mango crops, Salem seamlessly blends industry with agriculture.
    </font>
  </p>
</body>
</html>

hill.html

<!DOCTYPE html>
<html>
<head>
  <title>My Home Town</title>
</head>
<body bgcolor="cyan">
  <h1 align="center">
    <font color="red"><b>Salem</b></font>
  </h1>
  <h3 align="center">
    <font color="blue"><b>HILL-Hill station</b></font>
  </h3>
  <hr size="3" color="red">
  <p align="justify">
    <font face="Georgia" size="5">
        Perched about 1,515 meters above sea level in the Shevaroy Hills, Yercaud is Salem’s quintessential hill station—often called the “Jewel of the South.” Misty mornings here reveal emerald-green coffee and spice plantations that spill down rolling slopes, while winding roads climb through dense shola forests, offering vantage points such as Lady’s Seat and Pagoda Point with sweeping views over the plains below.
    </font>
  </p>
</body>
</html>

mecheri.html

<!DOCTYPE html>
<html>
<head>
  <title>My Home Town</title>
</head>
<body bgcolor="cyan">
  <h1 align="center">
    <font color="red"><b>Salem</b></font>
  </h1>
  <h3 align="center">
    <font color="blue"><b>Mecheri - The market</b></font>
  </h3>
  <hr size="3" color="red">
  <p align="justify">
    <font face="Georgia" size="5">Mecheri is a bustling town located in the northwestern part of Salem district, known primarily for its thriving textile and agriculture industries. Often dubbed the “Mecheri Sheep City,” it’s famous for the hardy Mecheri breed of sheep, whose wool and meat contribute significantly to the local economy.</font>
  </p>
</body>
</html>

tirumanur.html

<!DOCTYPE html>
<html>
<head>
  <title>My Home Town</title>
</head>
<body bgcolor="cyan">
  <h1 align="center">
    <font color="red"><b>Salem</b></font>
  </h1>
  <h3 align="center">
    <font color="blue"><b>Tirumanur - The Temple city</b></font>
  </h3>
  <hr size="3" color="red">
  <p align="justify">
    <font face="Georgia" size="5">Tirumanur is a serene village nestled in the verdant foothills of the Eastern Ghats within Salem district, just a short drive southeast of Salem city. Framed by lush agricultural fields, the village is renowned for its jackfruit orchards and paddy cultivation, which sustain the local economy and lend the landscape a patchwork of vibrant green.</font>
  </p>
</body>
</html>

tumbal.html

<!DOCTYPE html>
<html>
<head>
  <title>My Home Town</title>
</head>
<body bgcolor="cyan">
  <h1 align="center">
    <font color="red"><b>Salem</b></font>
  </h1>
  <h3 align="center">
    <font color="blue"><b>Tumbal - Busy city</b></font>
  </h3>
  <hr size="3" color="red">
  <p align="justify">
    <font face="Georgia" size="5">Tumbal is a quaint rural hamlet situated in the southwestern reaches of Salem district, tucked into the gentle undulations of the Eastern Ghats’ foothills. Predominantly an agrarian settlement, its red-soil fields yield turmeric, millets, and groundnuts, while small groves of tamarind and guava offer seasonal fruits to local markets </font>
  </p>
</body>
</html>


```

# OUTPUT
![alt text](1.png)
![alt text](2.png)
![alt text](3.png)
![alt text](4.png)
![alt text](5.png)
![alt text](6.png)


# RESULT
The program for implementing image maps using HTML is executed successfully.
