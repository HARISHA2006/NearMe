# Ex04 Places Around Me
## Date: 27-03-2024

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
map.html
```
<html>
    <head>
        <title>CHIDAMBARAM</title>
    </head>
    <body bgcolor="LIGHTBLUE">
        <h1>CHIDAMBARAM CITY</h1>
        <h3>Name: HARISHA S </h3>
        <h3>Reg no:212223040063</h3>
        <img src="MAP1.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="mangrove forest pichavaram" title="mangrove forest pichavaram" href="mangrove.html" coords="1779,147,93" shape="circle">
    <area target="" alt="thillai nataraja temple" title="thillai nataraja temple" href="temple.html" coords="1122,420,69" shape="circle">
    <area target="" alt="lmangrove bay ecocamp" title="lmangrove bay ecocamp" href="ecocamp.htmL" coords="1671,482,80" shape="circle">
    <area target="" alt="annamalai university" title="annamalai university" href="annamalai.html" coords="1294,482,72" shape="circle">
    <area target="" alt="krishna mahal" title="krishna mahal" href="mahal.html" coords="1108,230,103" shape="circle">
</map>
    </body>
</html>
```
annamalai.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="blue">
        <h1 align="center">
        <font color="gold"><b>chidambaram</b></font>
        </h1>
        <h3 align="center">
        <font color="pink"><b>annamalai university</b></font>
        </h3>
        <hr size="3" color="green">
        <p align="justify">
        <font face="Georgia" size="5">
            Annamalai University is a public residential university in Tamil Nadu, offering UG, PG, Research and Distance Education programs in various disciplines. Learn about its eligibility, selection procedure,
        </font>
        </p>
    </body>
</html>
```
mahal.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
        <font color="gold"><b>chidambaram</b></font>
        </h1>
        <h3 align="center">
        <font color="pink"><b>krishna mahal</b></font>
        </h3>
        <hr size="3" color="orange">
        <p align="justify">
        <font face="Georgia" size="5">
            Sri Krishna Grand Mahal. CMFV+2RF, Chennai - Nagapattinam Hwy, LNC Nagar, Chidambaram, Lalpuram, Tamil Nadu 608002, Chidambaram, Lalpuram, 608002. Contact Now. Write a Review.
        </font>
        </p>
    </body>
</html>
```
ecocamp.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
        <font color="orange"><b>chidambaram</b></font>
        </h1>
        <h3 align="center">
        <font color="purple"><b>mangrove ecocamp</b></font>
        </h3>
        <hr size="3" color="pink">
        <p align="justify">
        <font face="Georgia" size="5">
            Mangrove Bay Eco Camp. Located in the Cuddalore district, 10-acre campus, situated in north side bank of River Kollidam. Our Campus is a beautiful place tucked away in the serene
        </font>
        </p>
    </body>
    ```
    temple.html
    ```
    <html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
        <font color="gold"><b>chidambaram</b></font>
        </h1>
        <h3 align="center">
        <font color="purple"><b>thillai nataraja temple</b></font>
        </h3>
        <hr size="3" color="grey">
        <p align="justify">
        <font face="Georgia" size="5">
            Thillai Nataraja Temple is a Hindu temple dedicated to Lord Shiva located in Chidambaram, Tamil Nadu, South India. It is known as the foremost of all temples to Saivites and has influenced worship,
        </font>
        </p>
    </body>
</html>
```
mangrove.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="YELLOW">
        <h1 align="center">
        <font color="gold"><b>chidambaram</b></font>
        </h1>
        <h3 align="center">
        <font color="RED"><b>mangrove forest</b></font>
        </h3>
        <hr size="3" color="RED">
        <p align="justify">
        <font face="Georgia" size="5">
            Mangrove forests, also called mangrove swamps, mangrove thickets or mangals, are productive wetlands that occur in coastal intertidal zones. Mangrove forests grow mainly at tropical and
        </font>
        </p>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-03-26 231624.png>) ![alt text](<Screenshot 2024-03-26 231539.png>) ![alt text](<Screenshot 2024-03-26 231119.png>) ![alt text](<Screenshot 2024-03-26 231107.png>) ![alt text](<Screenshot 2024-03-26 230902.png>) ![alt text](<Screenshot 2024-03-26 230846.png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
