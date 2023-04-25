# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Create a new Django project.
### Step 2:
Add a view and template to your Django project
### Step 3:
Take screenshots of places around your house using Google Maps.

https://www.google.com/maps/@13.0262105,80.0169595,304m/data=!3m1!1e3.
### Step 4:
Identify a minimum of five different locations and mark them using image maps.

https://www.image-maps.com/
### Step 5:
Develop a webpage(minimum of 50 words) for each location and link it to the image region

## Code:
index.html
```
<!DOCTYPE html>
<html>
    <head>
        <title>
            Image Map
        </title>
    </head>
    <body >
        <h1 align="center" >
            <font color="red" >
                    Image Map Of My Home Town
            </font>

            
        </h1>
        <h3 align="center">
        <font color="blue" face ="cursive">
            SATHISH R (212222100048)
        </font>
            
        </h3>
        <center>
        <img id="Image-Maps-Com-image-maps-2023-04-18-204107" src="mymap.jpeg" border="0" width="1828" height="788" orgWidth="1828" orgHeight="788" usemap="#image-maps-2023-04-18-204107" alt="" />
        <map name="image-maps-2023-04-18-204107" id="ImageMapsCom-image-maps-2023-04-18-204107">
            <area  alt="" title="Temple" href="temple.html" shape="rect" coords="1198,726,1248,776" style="outline:none;" target="_self"     />
            <area  alt="" title="College" href="college.html" shape="rect" coords="1526,261,1576,311" style="outline:none;" target="_self"     />
            <area  alt="" title="My home" href="home.html" shape="rect" coords="963,671,1013,721" style="outline:none;" target="_self"     />
            <area  alt="" title="School" href="school.html" shape="rect" coords="404,129,454,179" style="outline:none;" target="_self"     />
            <area  alt="" title="Bakery" href="shop.html" shape="rect" coords="465,421,515,471" style="outline:none;" target="_self"     />
            <area shape="rect" coords="1826,786,1828,788" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
        </map>

        </center>
        <p align="center">
            <font color="maroon"  face="Comic Sans MS" >
                This Image Map shows various locations around my home.<br>
                Click the location and get information about it.
            </font>
        </p>

    </body>
</html>
```
home.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        HOME
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        MY HOME
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
			<LI>This is my home where I live happy with my family.<br></LI>		
			<LI>My mother and Father take cares of me and I have fun with my siblings and my pets.<br></LI>
            <LI>My pets are the loved ones because they keep me always engaging.<br></LI>
            <LI>When I feel stress, I used to visit my farms around my house and the nature and its beauty makes me to feel better.<br></LI>
		</OL>

    </font>
    <font color ="red" face = "cursive" size="16" > 
    "HOME IS WHERE OUR STORY BEGINS"
    </font>


</p>

</body>

</html>
```
school.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        SCHOOL
    </title>
</head>
<body>
<h1 align="center">
    <font color="blue" face="cursive" size >
        GOVT. UNION MIDDLE SCHOOL
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        A school is an educational institution designed to provide learning spaces and learning environments for the teaching of students under the direction of teachers.<br>
        Most countries have systems of formal education, which is sometimes compulsory. In these systems, students progress through a series of schools. <br>
        The names for these schools vary by country but generally include primary school for young children and secondary school for teenagers who have completed primary education.<br>
        An institution where higher education is taught is commonly called a university college or university. <br>
    </font>
    <font color ="red" face = "monospace" size ="16"> 
       "Learn as much as you can while you are young, since life becomes too busy later."
    </font>


</p>

</body>

</html>
```
temple.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        TEMPLE
    </title>
</head>
<body>
<h1 align="center">
    <font color="blue" face="cursive" size >
        Nagalamman Temple    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        A Hindu temple is a symbolic house, the seat and dwelling of Hindu gods.<br>
        It is a structure designed to bring human beings and gods together according to Hindu faith.<br>
        Inside its garbhagriha innermost sanctum, a Hindu temple contains a murti or Hindu god's image.<br> 
        Hindu temples are large and magnificent with a rich history.<br>
        There is evidence of use of sacred ground as far back as the Bronze Age and later during the Indus Valley civilization.<br>
    </font>
    <font color ="red" face = "monospace" size ="16"> 
        "The temple of our purest thoughts is silence." 
    </font>


</p>

</body>

</html>
```
college.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        COLLEGE
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive" size >
        Bharathidasan Engineering College
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        A college (Latin: collegium) is an educational institution or a constituent part of one.<br>
        A college may be a degree-awarding tertiary educational institution, a part of a collegiate or federal university,<br>
        An institution offering vocational education, or a secondary school. <br>
    </font>
    <font color ="red" face = "monospace" size ="16" > 
       "A College degree is not a sign of finished product but an indication a person is prepared for life"
    </font>


</p>

</body>

</html>
```
shop.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        SHOP
    </title>
</head>
<body  >
<h1 align="center">
    <font color="blue" face="cursive" size >
        BAKERY
    </font>
</h1>
<p align="center">
    <font color="black" size="24"face="Comic Sans MS">   
        A bakery is an establishment that produces and sells flour-based food baked in an oven such as bread, cookies, cakes, doughnuts, bagels, pastries, and pies.<br>
        Some retail bakeries are also categorized as cafés, serving coffee and tea to customers who wish to consume the baked goods on the premises.<br>
        Confectionery items are also made in most bakeries throughout the world.<br>
    </font>
    <font color ="red" face = "monospace" size ="16"> 
       "The more you know, the more you can create. There's no end to imagination in the kitchen.”
    </font>


</p>

</body>

</html>
```
## Output:
### MAP
![MAP](mymap.jpeg)
### HOME
![HOME](home.png)
### SCHOOL
![SCHOOL](school.png)
### TEMPLE
![TEMPLE](temple.png)
### COLLEGE
![College](college.png)
### SHOP
![SHOP](shop.png)


## Result:
Thus the locations are located and their informations are linked using HTML code.
