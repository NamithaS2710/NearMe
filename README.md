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
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Namitha S</title>
</head>
<script>
    function coord(event) {
        let x = event.clientX;
        let y = event.clientY;
        document.getElementById("txt1").value = x;
        document.getElementById("txt2").value = y;
    }
</script>

<body>
    <img src="Restaurant.jpeg" width="1000px" usemap="#MapNew" onmousemove="coord(event)">
    <MAP name="MapNew">
        <AREA shape="RECT" coords="100,181,236,245" href="https://restaurant-guru.in/HUNGER-SPOT-RESTAURANT-PAMMAL-Chennai" title="Hunger Spot">
        <AREA shape="RECT" coords="804,118,968,170" href="https://copperkitchen.in/" title="Kopper Kitchen">
        <AREA shape="RECT" coords="345,273,496,321"
            href="https://magicpin.in/Chennai/Pallavaram/Restaurant/Black-Pepper-Family-Restaurant/store/368aa8/" title="Black Pepper">
        <AREA shape="RECT" coords="566,323,724,365" href="https://restaurant-guru.in/Crescent-Restaurant-Keelkattalai-Chennai" title="Cresent Restaurant">
        
    </MAP>
    <br>
    X coord : <input type="text" name="" id="txt1"> <br>
    Y coord : <input type="text" name="" id="txt2">
</body>

</html>
```
## OUTPUT

![WhatsApp Image 2024-04-25 at 08 28 24](https://github.com/NamithaS2710/NearMe/assets/133190822/af8f61d4-56fa-4cf7-b4c7-9b0413a457d8)

## RESULT
The program for implementing image maps using HTML is executed successfully.
