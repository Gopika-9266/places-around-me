# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Write your own steps here.
### Step 2:
Create a new Django project.
### Step 3:
Write the needed HTML code.
### Step 4:
Run the Django server and execute the HTML files.

## Code:
```
Map.html:

<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b> Gopika R (212222240031) </b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCity" height="550" width="1100">
<map name="MyCity">
<area shape="circle" coords="190,50,20" href="/static/html/college.html" title="College">
<area shape="rectangle" coords="230,30,260,60" href="/static/html/fort.html" title="Fort">
<area shape="circle" coords="400,350,50" href="/static/html/temple.html" title="Temple">
<area shape="circle" coords="400,200,75" href="/static/html/hospital.html" title="Hospital">
<area shape="rectangle" coords="490,150,870,320" href="/static/html/hills.html" title="Hills">
</map>
</center>
</body>
```

```
College.html:

<!DOCTYPE html>
<html lang="en">
<head>
<title>College</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b> Vellore </b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Thanthai Periyar Government College</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Permanentmarker" size="5">
<b>
The Thanthai Periyar Government Institute of Technology is a government engineering institution located at Bagayam, Vellore. It was established in July 1990 and is one of the six government engineering colleges fully governed by the Directorate of Technical Education of the Government of Tamil Nadu.
</b>
</font>
</p>
</body>
</html>
```

```
Fort.html:

<!DOCTYPE html>
<html lang="en">
<head>
<title>Fort</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Vellore Fort</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Permanentmarker" size="5">
<b>
Vellore Fort is a large 16th-century fort situated in heart of the Vellore city, in the state of Tamil Nadu, India built by Vijayanagara kings.The fort was at one time the headquarters of the Aravidu Dynasty of the Vijayanagara Empire. The fort is known for its grand ramparts, wide moat and robust masonry. 
</b>
</font>
</p>
</body>
</html>
```

```
Temple.html:

<!DOCTYPE html>
<html lang="en">
<head>
<title>Fort</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Sri Narayani Golden Temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Permanentmarker" size="5">
<b>
Golden Temple Vellore complex inside the Thirupuram spiritual park is situated at the foot of a small range of green hills at Thirumalaikodi Vellore in Tamil Nadu, India. It is 120 km from Tirupati, 145 km from Chennai, 160 km from Pondicherry and 200 km from Bengaluru.
</b>
</font>
</p>
</body>
</html>
```

```
Hospital.html:

<!DOCTYPE html>
<html lang="en">
<head>
<title>CMC Hospital </title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Christian Medical College (CMC)</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="PermanentMarker" size="5">
<b>
Christian Medical College, Vellore, widely known as CMC, Vellore, is a private, Christian community-run medical school, hospital and research institute.One of the top-ranked educational, healthcare and research institutes in the country. This Institute includes a network of primary, secondary and tertiary care hospitals in and around Vellore,Tamil Nadu, India.
</b>
</font>
</p>
</body>
</html>
```

```
Hills.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Hills</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Palamathi Hills</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="PermanentMarker" size="5">
<b>
The Palamathi Hills are an extension of the Eastern Ghats spread across southeastern parts of Vellore City in Tamil Nadu. The Palamathi Hill range, the nearby Palamathi Reserve Forest, the Otteri lake is collectively referred to as Palamathi Hills. The area is a thriving hotspot for various birds and various flora.
</b>
</font>
</p>
</body>
</html>
```
## Output:

![Screenshot (123)](https://user-images.githubusercontent.com/122762773/235728474-9e39e786-53db-4007-bb28-94f00a09a179.png)


![Screenshot (116)](https://user-images.githubusercontent.com/122762773/235728602-58466470-ce52-40f2-8ebf-6c9771929485.png)


![Screenshot (115)](https://user-images.githubusercontent.com/122762773/235728655-3ea3ce2b-d62f-4a08-a30b-8e3c2c812787.png)


![Screenshot (114)](https://user-images.githubusercontent.com/122762773/235728704-7bf7014a-e186-45e8-bf56-6543adc00891.png)


![Screenshot (112)](https://user-images.githubusercontent.com/122762773/235728853-f3bcd32a-6830-40f0-a19c-f0017d1c983e.png)


![Screenshot (113)](https://user-images.githubusercontent.com/122762773/235728778-fc887595-6fcc-4d1c-8f25-34e444762e50.png)


![Screenshot (124)](https://user-images.githubusercontent.com/122762773/235729003-0cb7b7c5-e884-4312-aad3-c190eb67c3b9.png)


![Screenshot (125)](https://user-images.githubusercontent.com/122762773/235729052-6f54e3cc-7841-4fe6-980c-a4f5022b5a3c.png)

## Result:
Thus A website to display details about the places in map is successfully executed and displayed.
