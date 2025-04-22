# Ex04 Places Around Me
## Date: 

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

### MAP.HTML
```
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>ARNTHANGI :)</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>KARTHIKEYAN D (212224230115)</b></font>
</h3>
<center>
<img src="IMG.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700,250,850,400" href="home.html" title="home">
<area shape="circle" coords="570,230,45" href="Suba.html" title="Suba">
<area shape="circle" coords="640,200,30" href="idaiyar.html" title="idaiyar">
<area shape="circle" coords="1120,360,25" href="Hospital.html" title="Hospital">
<area shape="rect" coords="950,120,1100,140" href="KalayanaMahal.html" title="KalayanaMahal">
</map>
</center>
</body>
</html>
```
### Suba.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Styled Paragraphs</title>
</head>
<body style="background-color: red;">

    <h1 style="text-align: center; color: darkblue; font-size: 36px; font-family: Georgia, serif;">
       SUBA INFO
    </h1>
<!-- Red Background Paragraph -->
<p style="color: white; font-size: 36px; font-family: Arial, sans-serif; background-color: red; padding: 10px; border: 1px solid #ccc; border-radius: 8px;">
    Suba Theatre is a well-known cinema hall or theatre located in various regions of India, with a reputation for screening a wide range of films, including mainstream commercial movies, regional films, and sometimes independent cinema. The theatre is often celebrated for its traditional charm and connection to the local community, offering a space where moviegoers can enjoy a cinematic experience in a comfortable setting. While many theatres have evolved with modern amenities, Suba Theatre may retain a classic appeal with its nostalgic atmosphere, catering to movie enthusiasts seeking both entertainment and a sense of cultural connection. The significance of Suba Theatre often extends beyond just movie screenings, as it may serve as a venue for special events, film festivals, or local gatherings, making it an important part of the cultural fabric of the area.
</p>

</body>
</html>
```
### Mahal.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Styled Paragraphs</title>
</head>
<body style="background-color: red;">

    <h1 style="text-align: center; color: darkblue; font-size: 36px; font-family: Georgia, serif;">
        KalayanaMahal INFO
    </h1>
<!-- Red Background Paragraph -->
<p style="color: white; font-size: 36px; font-family: Arial, sans-serif; background-color: red; padding: 10px; border: 1px solid #ccc; border-radius: 8px;">
    A Kalyana Mahal, also known as a Kalyana Mandapam, is a traditional wedding hall commonly found in South India, particularly in Tamil Nadu. These venues are specifically designed to host weddings and other cultural or religious ceremonies. They are characterized by their grand and elegant architecture, featuring intricate designs, large halls, and decorative elements that reflect the cultural heritage of the region. Kalyana Mahals are spacious, with facilities that can accommodate hundreds to thousands of guests, providing a perfect setting for wedding celebrations. The halls are equipped with modern amenities while retaining traditional charm, offering services like catering, decoration, and audio-visual arrangements. These venues are central to the cultural fabric of South Indian weddings, providing a blend of tradition, comfort, and functionality for one of the most significant events in a person's life.
</p>

</body>
</html>
```
### Hospital
```
<!DOCTYPE html>
<html>
<head>
    <title>HOSPITAL :)</title>
</head>
<body style="background-color: red;">

    <h1 style="text-align: center; color: darkblue; font-size: 36px; font-family: Georgia, serif;">
        HOSPITAL INFO
    </h1>
<!-- Red Background Paragraph -->
<p style="color: white; font-size: 36px; font-family: Arial, sans-serif; background-color: red; padding: 10px; border: 1px solid #ccc; border-radius: 8px;">
    A hospital is a healthcare facility that provides medical treatment, care, and support to individuals who are ill, injured, or in need of medical attention. Hospitals are equipped with specialized staff, including doctors, nurses, and technicians, who work together to diagnose, treat, and manage a wide range of health conditions.
Hospitals typically offer a variety of services such as emergency care, surgical procedures, maternity care, diagnostic testing, and rehabilitation. They can vary in size and scope, from small community clinics to large, multi-specialty medical centers offering advanced treatments. In addition to providing physical care, hospitals also focus on mental health services, patient education, and preventive care.
Key areas within a hospital include the emergency department (ED), operating rooms, intensive care units (ICUs), outpatient clinics, and patient wards. Hospitals play a critical role in public health systems by addressing both urgent and long-term health needs, ensuring that patients receive timely and effective care. The infrastructure and resources of a hospital are designed to create a safe environment for both patients and healthcare providers, prioritizing cleanliness, patient comfort, and efficient healthcare delivery.
</p>

</body>
</html>
```
### Idaiyar.html

```
<!DOCTYPE html>
<html>
<head>
    <title>Idaiyar</title>
</head>
<body style="background-color: red;">

    <h1 style="text-align: center; color: darkblue; font-size: 36px; font-family: Georgia, serif;">
        IDAIYAR INFO
    </h1>
<!-- Red Background Paragraph -->
<p style="color: white; font-size: 36px; font-family: Arial, sans-serif; background-color: red; padding: 10px; border: 1px solid #ccc; border-radius: 8px;">
    Idaiyar is a traditional term often used to refer to a person who follows or is associated with a particular region, community, or cultural group in South India. While the specific meaning of "Idaiyar" can vary depending on the context and region, it is generally a label used for certain social groups, often in Tamil Nadu, and is sometimes linked to the agricultural or pastoral communities. The term might also carry historical significance, with associations to specific customs, language, or practices within a localized area. Understanding the role of Idaiyar within the broader framework of South Indian society requires looking at the specific cultural, social, and historical nuances tied to this group.
</p>

</body>
</html>
```


## OUTPUT

[text](myproj/mapapp/static/home.html) 

[text](myproj/mapapp/static/Suba.html) 

[text](myproj/mapapp/static/KalayanaMahal.html) 

[text](myproj/mapapp/static/Hospital.html) 

[text](myproj/mapapp/static/idaiyar.html)



## RESULT
The program for implementing image maps using HTML is executed successfully.
