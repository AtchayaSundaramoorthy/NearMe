# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
clone the github repository into Theia IDE.

### Step 2:
Create a new Django project.

### Step 3:
Download city map from google.

### Step 4:
Create clickable regions in image file using <map> element.

### Step 5:
Execute the html file.


### Step 6:
Publish the URL and validate it.

## Code:
```
map.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Redhills</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Atchaya S (22000184)</b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="190,50,20" href="/static/html/vtec.html" title="Vel Tech Engineering College">
<area shape="rectangle" coords="230,30,260,60" href="/static/html/vec.html" title="Velammal Engineering College">
<area shape="circle" coords="400,350,50" href="/static/html/pl.html" title="Puzhal Lake">
<area shape="circle" coords="400,200,75" href="/static/html/twie.html" title="Thirumullaivoyal Womens Industrial Estate">
<area shape="rectangle" coords="490,150,870,320" href="/static/html/cccr.html" title="CSS Computer College Redhills">
</map>
</center>
</body>
</html>




vtec.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Engineering College>
</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Redhills</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Vel Tech Engineering College">
</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
 Sengundram, known in English as Red Hills, is a neighbourhood in the northwestern part of Chennai, Tamil Nadu, India. The name was derived from the red hills (Semman Kuviyal) that was formerly present in the area.
</b>
</font>
</p>
</body>
</html>

vec.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Velammal Engineering College</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Redhills</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Velammal Engineering College</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
The Velammal Educational Trust is a registered non-minority service organization established in the year 1986 by Thiru. M.V. Muthuramalingam inculcates among the youth a sense of discipline which is important to mould them into useful and capable citizens. The watchwords of the Trust are “Dedication, Determination, and Distinction”.
Velammal Engineering College was established in the year 1995-96 to impart quality education. It is a self-financing non-minority institution, affiliated to Anna University and approved by the All India Council for Technical Education (AICTE) and also an ISO-certified institution.
</font>
</p>
</body>
</html>
pl.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Puzhal Lake</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Redhills</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Puzhal Lake</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
The Pulhal reservoir was built in 1876 during the British rule in Pulhal, Chennai, The reservoir was originally a small tank with a capacity of 500 million cubic feet (mcft) and two masonry weirs, built using locally available laterite stones, then functioned as surplus weirs to release excess water from the water body. Today, these masonry weirs are water-retaining structures as they have been replaced by two shutters. In 1997, the storage capacity of the water reservoir was increased to 3,300 mcft and the depth to 21.20 ft to cater to the drinking water needs of Chennai and also to store Krishna river water received from Andhra Pradesh through Poondi Reservoir and the Sholavaram Tank. Until 2012, the Water Resources Department (WRD) has only taken up maintenance work worth of ₹ 500,000 every year.[1]
</b>
</font>
</p>
</body>
</html>

twie.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Thirumullaivoyal Womens Industrial Estate</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Redhills</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Thirumullaivoyal Womens Industrial Estate</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Thirumullaivoyal is a western neighbourhood of Chennai, the capital of the Indian state of Tamil Nadu. It is located in the Chennai Metropolitan Area in Tiruvallur district, 2 km (1.2 mi) from Ambattur. The neighbourhood is served by Thirumullaivoyal railway station and Annanur Railway Station. The region was historically part of Thondaimandalam, a region in Chola Empire during 9th century CE.

The place was originally called Mullaivanam, a forest, after which the suburb is named. The history of the suburb revolves around the Masilmaninathar temple. The place is also one of the five revenue firkas under the Avadi Taluk.[1] The place is a pilgrimage location and also houses several other religious and natural tourist destinations.
</font>
</p>
</body>
</html>



cccr.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>CSS Computer College Redhills</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Redhills</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>CSS Computer College Redhills</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
"Computer Training Institute, Tally Training Institute, Autocad Training Institute, Java Training Institute, Python Training Institute, DTP Training Institute, C++ Training Institute, Photoshop Training Institute, Computer Basics Training Institute, MS Office Training Institute, Coraldraw Training Institute, CAD Training Institute, Multimedia Training Institute"
</font>
</p>
</body>
</html>

cccr.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>CSS Computer College Redhills</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Redhills</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>CSS Computer College Redhills</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
"Computer Training Institute, Tally Training Institute, Autocad Training Institute, Java Training Institute, Python Training Institute, DTP Training Institute, C++ Training Institute, Photoshop Training Institute, Computer Basics Training Institute, MS Office Training Institute, Coraldraw Training Institute, CAD Training Institute, Multimedia Training Institute"
</font>
</p>
</body>
</html>

pl.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Puzhal Lake</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Redhills</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Puzhal Lake</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
The Pulhal reservoir was built in 1876 during the British rule in Pulhal, Chennai, The reservoir was originally a small tank with a capacity of 500 million cubic feet (mcft) and two masonry weirs, built using locally available laterite stones, then functioned as surplus weirs to release excess water from the water body. Today, these masonry weirs are water-retaining structures as they have been replaced by two shutters. In 1997, the storage capacity of the water reservoir was increased to 3,300 mcft and the depth to 21.20 ft to cater to the drinking water needs of Chennai and also to store Krishna river water received from Andhra Pradesh through Poondi Reservoir and the Sholavaram Tank. Until 2012, the Water Resources Department (WRD) has only taken up maintenance work worth of ₹ 500,000 every year.[1]
</b>
</font>
</p>
</body>
</html>

twie.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Thirumullaivoyal Womens Industrial Estate</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Redhills</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Thirumullaivoyal Womens Industrial Estate</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Thirumullaivoyal is a western neighbourhood of Chennai, the capital of the Indian state of Tamil Nadu. It is located in the Chennai Metropolitan Area in Tiruvallur district, 2 km (1.2 mi) from Ambattur. The neighbourhood is served by Thirumullaivoyal railway station and Annanur Railway Station. The region was historically part of Thondaimandalam, a region in Chola Empire during 9th century CE.

The place was originally called Mullaivanam, a forest, after which the suburb is named. The history of the suburb revolves around the Masilmaninathar temple. The place is also one of the five revenue firkas under the Avadi Taluk.[1] The place is a pilgrimage location and also houses several other religious and natural tourist destinations.
</font>
</p>
</body>
</html>

vec.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Velammal Engineering College</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Redhills</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Velammal Engineering College</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
The Velammal Educational Trust is a registered non-minority service organization established in the year 1986 by Thiru. M.V. Muthuramalingam inculcates among the youth a sense of discipline which is important to mould them into useful and capable citizens. The watchwords of the Trust are “Dedication, Determination, and Distinction”.
Velammal Engineering College was established in the year 1995-96 to impart quality education. It is a self-financing non-minority institution, affiliated to Anna University and approved by the All India Council for Technical Education (AICTE) and also an ISO-certified institution.
</font>
</p>
</body>
</html>

vtec.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Engineering College>
</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Redhills</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Vel Tech Engineering College">
</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
 Sengundram, known in English as Red Hills, is a neighbourhood in the northwestern part of Chennai, Tamil Nadu, India. The name was derived from the red hills (Semman Kuviyal) that was formerly present in the area.
</b>
</font>
</p>
</body>
</html>
```

## Output:
![Output](./out1.png)
![Output](./out2.png)
![Output](./out3.png)
![Output](./out4.png)
![Output](./out5.png)
![Output](./out6.png)

## HTML Validator
![Output](./valid.png)

## Result:
The program executed successfully.