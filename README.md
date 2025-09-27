# Ex04 Places Around Me
## Date: 20/9/25


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
````
map.html
<html>
    <head>
        <title>MAP</title>
    </head>
        <body>
            <h1 align="center">VILLUPURAM</h1>
            <h2 align="center">LEKSHMEENDHRA S(25016379)</h2>

             <img src="map.png"height="440"width="1000" usemap="#image-map">

            <map name="image-map">
               <area target="" alt="Golden park" title="Golden park" href="park.html" coords="350,350,460,460" shape="rect">
               <area target="" alt="New Bus Stand" title="New Bus Stand" href="bus stand.html" coords="350,350,80" shape="circle">
               <area target="" alt="VVA Meenakshi Mahal" title="VVA Meenakshi Mahal" href="vva.html" coords="200,200,200,200,500,500,900,200,200,300,200,200,200,500,200,700,300,300,300,500,300,300" shape="poly">
               <area target="" alt="Hotel Balaji INN villupuram" title="Hotel Balaji INN villupuram" href="hotel.html" coords="200,200,600,600" shape="rect">
               <area target="" alt="KAKUPPAM" title="KAKUPPAM" href="kakuppam.html" coords="100,100,700" shape="circle">
            </map>
        </body>
</html>
bus stand.html
<html>
    <head1>
        <title>busstand</title>
    </head1>
    <body bgcolor="red" text="yellow">
        <h1>BUS STAND</h1>
    </body>
</html>
kakuppam.html
<html>
    <head1>
        <title>kakuppam</title>
    </head1>
    <body bgcolor="green" text="yellow">
        <h1>KAKUPPAM</h1>
    </body>
</html>
hotel.html
<html>
    <head1>
        <title>hotel</title>
    </head1>
    <body bgcolor="red" text="black">
        <h1>HOTEL BALAJI</h1>
    </body>
</html>
VVA.html
<html>
    <head1>
        <title>HALL</title>
    </head1>
    <body bgcolor="pink" text="purple">
        <h1>VVA MAHAL</h1>
    </body>
</html>
park.html
<html>
    <head1>
        <title>park</title>
    </head1>
    <body bgcolor="black" text="white">
        <h1>Golden PARK</h1>
    </body>
</html>


````


## OUTPUT
![alt text](<Screenshot 2025-09-21 001639.png>)
![alt text](<Screenshot 2025-09-21 001715.png>)
![alt text](<Screenshot 2025-09-21 001746.png>)
![alt text](<Screenshot 2025-09-21 001805.png>)
![alt text](<Screenshot 2025-09-21 001822.png>)
![alt text](<Screenshot 2025-09-21 001838.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
