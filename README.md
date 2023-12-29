NAME: Naveen G
REFERENCE NUMBER :212223220066
# Places Around Me
# Aim:
To develop a website to display details about the places around my house.

# Design Steps:
## Step 1
1. Fork and Clone the GitHub repository.

2. Create a new Django project.

## Step 2
3. Add a view and template to your Django project

4. Take screenshots of places around your house using Google Maps.

https://www.google.com/maps/@13.0262105,80.0169595,304m/data=!3m1!1e3.

5. Identify a minimum of five different locations and mark them using image maps.

https://www.image-maps.com/

## Step 3
6. Develop a webpage(minimum of 50 words) for each location and link it to the image region.

7. Mention your domain URL and the GitHub Repo URL in the submission text and attach the lab report pdf.



# Code:
``````
<head>

    <title>My City</title>
    
</head>
    
<body>
    
<h1 align="center">
    
<font color="red"><b>Chittoor</b></font>
    
</h1>
    
<h3 align="center">
    
<font color="blue"><b>S.Harish(23000385)</b></font>
    
</h3>
    
<center>
    

<img src="![Screenshot 2023-11-29 081302](https://github.com/harishsivakumarj/Ex-04-webTech_imagemap/assets/145754113/625454a3-f064-46c2-9f1a-569ebf4a608f)
" usemap="#MyCity" height="610" width="1450">
    
<map name>="#MyCity"
    

<img src="![Screenshot 2023-11-29 081302](https://github.com/harishsivakumarj/Ex-04-webTech_imagemap/assets/145754113/e6373f1f-d1c5-4635-a395-487e371faa9c)
" usemap="#image-map"> 



<img src="![Screenshot 2023-11-29 081302](https://github.com/harishsivakumarj/Ex-04-webTech_imagemap/assets/145754113/c0081316-aee6-4bb7-a5fa-9d9fdfcc73ac)
" usemap="#image_map"> 
<map name="image_map">
  <area alt="Camford School" title="Camford School" href="school.html" coords="595,224,791,342" shape="rect">
  <area alt="Childerns Trust" title="Childerns Trust" href="trust.html" coords="573,58,58" shape="circle">
  <area alt="Vinayaka Temple" title="Vinayaka Temple" href="temple.html" coords="337,152 402,144 391,185 426,204 352,222 370,171 370,177 " shape="polygon">
  <area alt="Venkateshwara Silks" title="Venkateshwara Silks" href="clothing.html" coords="945,533,55" shape="circle">
  <area alt="Tech Park" title="Tech Park" href="computer center" coords="857,759,920,820" shape="rect">
</map>

</center>
    
</body>
    
</html>
<html>
    <head>
        <title>Camford School</title>
    </head>
    <body style="background-color: rgb(211, 78, 118); color: black; text-align: center;">
        <h1 style="font-size: 100px;"><b>CAMFORD SCHOOL</b></h1>
        <ul style="list-style-type: none; padding: 0;">
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; Camford is one of the Best schools in Chittoor</li>
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; The school is more important for Sports</li>
            <li style="margin-bottom: 10px; font-size: 25px;">&#9733;This school has big Play ground</li>
        </ul>
    </body>
</html>
<html>
    <head>
        <title>Childrens Trust</title>
    </head>
    <body style="background-color: lavender; color: black; text-align: center;">
        <h1 style="font-size: 100px;"><b>CHILDERNS TRUST</b></h1>
        <ul style="list-style-type: none; padding: 0;">
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733;This trust has more than 150 students.</li>
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; It is about 20-year-old trust.</li>
            <li style="margin-bottom: 10px; font-size: 25px;">&#9733;This is one the major trust in chittoor.</li>
        </ul>
    </body>
</html>
<html>
    <head>
        <title>Vinayaka Temple</title>
    </head>
    <body style="background-color: rgb(250, 250, 230); color: black; text-align: center;">
        <h1 style="font-size: 100px;"><b>VINAYAKA TEMPLE</b></h1>
        <ul style="list-style-type: none; padding: 0;">
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733;Vinayaka Temple works all days a week.</li>
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; It houses an about 40-year-old temple.</li>
            <li style="margin-bottom: 10px; font-size: 25px;">&#9733;The presiding deity is Ganapathy.</li>
        </ul>
    </body>
</html>
<html>
    <head>
        <title>Venkateshwara Silks</title>
    </head>
    <body style="background-color: rgb(230, 250, 231); color: black; text-align: center;">
        <h1 style="font-size: 100px;"><b>VENKATESHWARA SILKS</b></h1>
        <ul style="list-style-type: none; padding: 0;">
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; Venkateshwara lothing store in chittoor.</li>
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733;Venkateshwara is operational at 9am-10pm.</li>
            <li style="margin-bottom: 10px; font-size: 25px;">&#9733;Venkateshwara provides items at cheap rate.</li>
        </ul>
    </body>
</html>
<html>
    <head>
        <title>Tech Park</title>
    </head>
    <body style="background-color: rgb(250, 242, 230); color: black; text-align: center;">
        <h1 style="font-size: 100px;"><b>TECH PARK</b></h1>
        <ul style="list-style-type: none; padding: 0;">
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733;Tech park is one of the famous computer center in chittoor.</li>
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; It is more useful school (or) college students.</li>
            <li style="margin-bottom: 10px; font-size: 25px;">&#9733;It has more than 100 systems in the tech park.</li>
        </ul>
    </body>
</html>
``````


# Output:

![Screenshot 2023-11-29 081302](https://github.com/harishsivakumarj/Ex-04-webTech_imagemap/assets/145754113/391fadc6-0230-414b-9031-0240d5841d31)

![Screenshot 2023-11-29 090443](https://github.com/harishsivakumarj/Ex-04-webTech_imagemap/assets/145754113/de7377c1-22f3-4025-bfbc-ea6875d19232)

![Screenshot 2023-11-29 090540](https://github.com/harishsivakumarj/Ex-04-webTech_imagemap/assets/145754113/20553f4f-3e66-4cd5-ba47-f79981b18e75)

![Screenshot 2023-11-29 090618](https://github.com/harishsivakumarj/Ex-04-webTech_imagemap/assets/145754113/180077e9-c8bc-4791-b7e8-64cb7b4109bd)

![Screenshot 2023-11-29 090955](https://github.com/harishsivakumarj/Ex-04-webTech_imagemap/assets/145754113/12a01cf3-bf10-45f1-8a31-488036c525ee)

![Screenshot 2023-11-29 091022](https://github.com/harishsivakumarj/Ex-04-webTech_imagemap/assets/145754113/ecd348b2-d20e-4615-bffc-e578a2bbddc0)







# Result:
This Program Executed Successfully
