
# Ex04 Places Around Me
# Date:
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
map.html:
```
<html>
    <head>
        <title>MY CITY</title>
    </head>
    <body>
        <h1 align="center">
            <font color="blue"><b>vellore</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>deepika</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="mycity" height="610" width="1450">
            <map name="my city">
                <area shape="rect" coords="413,419,358,415" alt="Ractangle" href="star temple.html">
                <area shape="rect" coords="1037,543,1064,517" title="Ractangle" href="temple.html">
                <area shape="rect" coords="668,599,650,613" alt="Ractangle" href="fort.html">
                <area shape="circle" coords="544,208,18" alt="Circle" href="university.html">
                <area shape="circle" coords="1097,435,16" alt="Circle" href="hospital.html">
            </map>
        </center>
    </body>
</html>`
star temple.html:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GOLDEN TEMPLE</title>
  <style>
      h1 {
          color: red;
          text-align: center;
          font-size: 48px;
      }
      p {
          padding-top: 2%;
          font-size: 28px;
          padding-right: 5%;
          padding-left: 2%;
          color: blue;
      }
      body {
          background-color: yellow;
      }
  </style>
</head>
<body>
  <h1>GOLDEN TEMPLE</h1>
  <hr color="black">
  <p><b>
    The temple with its gold (1500 kg) covering, has intricate 
    work done by artisans specialising in temple art using gold.
    Every single detail was manually created, including converting 
    the gold bars into gold foils and then mounting the foils on copper.
      </b></p>
  <br><br>
  <hr color="black">
</body>
</html>
temple.html:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>VELLORE FORT TEMPLE</title>
  <style>
      h1 {
          color: rgb(0, 149, 255);
          text-align: center;
          font-size: 48px;
      }
      p {
          padding-top: 2%;
          font-size: 28px;
          padding-right: 5%;
          padding-left: 2%;
          color: blue;
      }
      body {
          background-color: rgb(202, 58, 212);
      }
  </style>
</head>
<body>
  <h1>FORT TEMPLE</h1>
  <hr color="black">
  <p><b>
    The fort houses the Jalakanteswarar Hindu temple, the Christian St. 
    John's Church and a Muslim mosque, of which the Jalakanteswarar Temple is famous for its magnificent carvings.
    The first significant military rebellion against British rule, the Vellore Mutiny, erupted at this fort in 1806.
      </b></p>
  <br><br>
  <hr color="black">
</body>
</html>
fort.html:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>VELLORE FORT</title>
  <style>
      h1 {
          color: red;
          text-align: center;
          font-size: 48px;
      }
      p {
          padding-top: 2%;
          font-size: 28px;
          padding-right: 5%;
          padding-left: 2%;
          color: blue;
      }
      body {
          background-color: yellow;
      }
  </style>
</head>
<body>
  <h1>VELLORE FORT</h1>
  <hr color="black">
  <p><b>
    Vellore Fort is a large 16th-century fort in the center of Vellore city, in the state of Tamil Nadu, India. 
    It was built by Vijayanagara kings. 
    The fort was at one time the headquarters of the Aravidu Dynasty of the Vijayanagara Empire.
    The fort has grand ramparts and wide moat.
      </b></p>
  <br><br>
  <hr color="black">
</body>
</html>
university.html:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>VIT UNIVERSITY</title>
  <style>
      h1 {
          color: rgb(225, 255, 0);
          text-align: center;
          font-size: 48px;
      }
      p {
          padding-top: 2%;
          font-size: 28px;
          padding-right: 5%;
          padding-left: 2%;
          color: rgb(0, 204, 255);
      }
      body {
          background-color: rgb(0, 162, 255);
      }
  </style>
</head>
<body>
  <h1>VIT UNIVERSITY</h1>
  <hr color="black">
  <p><b>
    Vellore Institute of Technology (VIT), previously Vellore Engineering College, is a deemed university in Vellore, Tamil Nadu.
     It has a history of innovation in higher education, expanding from 180 students to 67,000+.
      VIT emphasizes quality in teaching, research, and innovation, with a focus on student-centric learning.
      It has campuses in Vellore and Chennai, along with sister universities in other locations.
       VIT also has an international campus in Mauritius. 
    Vellore Institute of Technology - Wikipedia
    Vellore Institute of Technology or VIT is a private deemed university in Vellore, Tamil Nadu, India. 
    VIT University
    
      </b></p>
  <br><br>
  <hr color="black">
</body>
</html>
hospital.html:
<!DOCTYPE html>
 <html lang="en">
 <head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>CHRISTIAN MEDICAL COLLEGE</title>
   <style>
       h1 {
           color: red;
           text-align: center;
           font-size: 48px;
       }
       p {
           padding-top: 2%;
           font-size: 28px;
           padding-right: 5%;
           padding-left: 2%;
           color: blue;
       }
       body {
           background-color: yellow;
       }
   </style>
 </head>
 <body>
   <h1></h1>
   <hr color="black">
   <p><b>
    CMC Vellore, a private Christian minority-run medical college and hospital, is located in Vellore, Tamil Nadu, India.
    Founded in 1900 by Dr. Ida S. Scudder, it's known for pioneering medical advancements and a commitment to healthcare and education. 
    The institution has achieved numerous firsts in Indian medicine, including the first College of Nursing,
    reconstructive leprosy surgery, and successful open heart surgery.
 </b></p>
 <br><br>
 <hr color="black">
 </body>
 </html>
 ```
# OUTPUT
![university png](https://github.com/user-attachments/assets/3d2c2db4-34b6-409e-bfe5-ec15b889ce01)
![fort temple png](https://github.com/user-attachments/assets/33d47ddf-c2eb-4f97-95ac-c095cdde91dc)
![map](https://github.com/user-attachments/assets/12cee6f7-fe4a-4480-ab7f-7e9106d51527)
![fort png](https://github.com/user-attachments/assets/c5dc4e5c-f977-471f-9f64-b17e5f6a5660)
![golden temple png](https://github.com/user-attachments/assets/16729113-1c69-40be-8c76-a91c35e2e5a4)
![hospital png](https://github.com/user-attachments/assets/2ca7698d-7db3-42c5-9235-35777d952ecc)






# RESULT
The program for implementing image maps using HTML is executed successfully.
