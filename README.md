# Ex04 Places Around Me
## Date: 07/04/24

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
## Map.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Pothur</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>YOGESH V (212223230250)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#MyCity" height="610" width="1450">
            <map name="MyCity">
                <area shape="rect" coords="700,300,870,400" href="home.html" title="My Home Town">
                <area shape="circle" coords="900,410,45" href="temple.html" title="Sri Vembuli Amman Temple">
                <area shape="rect" coords="1050,370,1350,600" href="river.html" title="Puzhal Lake">
                <area shape="rect" coords="872,470,970,301" href="psm.html" title="PSM Sports Village">
            </map>
        </center>
    </body>
</html>
```
## Home.html
```
<html>
    <head>
        <title>
            My Home Town
        </title>
    </head>
    <body bgcolor="orange">
        
            <h1 align="center"><font color="red">POTHUR</font></h1>
            <h4 align="center" font="italic">
            <font color="blue"><h5 align="center" font="algerian"> Panchayat
            </h5></b>
            </font> 
            </h4>
            <hr size="3" color="red">
            <p align="justify">
                <font face="Georgia" size="5">
        

<br>Pothur is a small village in between the city.
<br>It is located in the bank of Puzhal lake.
<br>Before some centuries there were many Britishers lived in Pothur.
<br>Now the government had planned to excavate our area to find some old materials which were been burried.
</font>
</p>
</body>
</html>
```
## PSM.html
```
<html>
    <head>
        <title>
            My Home Town
        </title>
    </head>
    
        <body bgcolor="gray">
            <h1 align="center"><font color="red">Pothur</font></h1>
            <h4 align="center" font="italic">
            <font color="blue"><h5 align="center" font="algerian"> PSM Sports Village
            </h5></b>
            </font> 
            </h4>
            <hr size="3" color="red">
            <p align="justify">
                <font face="Georgia" size="5">
                <br>PSM Sports village - was inaugurated on 25/12/23. 
                <br>The ownser psm sports village is Mr.P.S.M.Vimal .
                <br>It is a cricket ground where matches will be played everyday.
                <br>It took about 2 years to finish constructing the ground.

                </font>
                </p>
</body>
</html>
```
## Lake.html
```
<html>
    <head>
        <title>
            My Home Town
        </title>
    </head>
    <body bgcolor="skyblue">
        <body bgcolor="gold">
            <h1 align="center"><font color="red">POTHUR</font></h1>
            <h4 align="center" font="italic">
            <font color="blue"><h5 align="center" font="algerian">Puzhal Lake -- Water Source
            </h5></b>
            </font> 
            </h4>
            <hr size="3" color="red">
            <p align="justify">
                <font face="Georgia" size="5">
        
        <br>Puzhal lake is located in Redhills,Chennai.
         <br>It lies in Thiruvallur district of TamilNadu.
          <br>It is one of the two rain fed reservoirs that supply water to chennai.
          <br> The primary inflow is 9607(cusecs) 
          <br>The primary outflow is 5470(cusecs) 
          <br>It was built in 1876.
          <br>It covers a surface area of about 4500 acres.
    </font>
    </p>
    </body>
    </html>
```
## Temple.html
```
<html>
    <head>
        <title>
            My Home Town
        </title>
    </head>
    <body bgcolor="gold">
        <h1 align="center"><font color="red">Pothur</font></h1>
        <h4 align="center" font="italic">
        <font color="blue">  <b>Arulmigu Sri Vembuli Amman Temple.</b>
        </font> 
        </h4>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
        <br>The temple was constructed several centuries before.
        <br>Since it was an old temple,people planned of reconstructing it.
        <br>So the new temple was contructed and consecration were held before i joined college.
        <br>The statues exposes the creativity and skills of the sculptors.
</font>
      </p>
    </body>
</html>
```
## OUTPUT
![alt text](<Screenshot 2024-04-07 004624.png>)
![alt text](<Screenshot 2024-04-07 004639.png>)
![alt text](<Screenshot 2024-04-07 004655.png>)
![alt text](<Screenshot 2024-04-07 004708.png>)
![alt text](<Screenshot 2024-04-07 004720.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
