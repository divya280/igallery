# Ex.08 Design of Interactive Image Gallery
## Date: 12.11.2024

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :

### image.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Gallery</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Satisfy&display=swap" rel="stylesheet">
</head>
<body>
    <h1>image gallery</h1>
    
    <div class="gallery">
        <div class="gallery-item"><img src="C:\Users\admin\Downloads\When to Harvest Sunflower Seeds — Meadowlark Journal.jpeg" alt="Image 1">
        <p style="font-family: cursive; font-size:30px;font-style:italic;"> Sunflower</p></div>
        <div class="gallery-item"><img src="C:\Users\admin\Downloads\Perennial Flowers for a Stunning Design.jpeg" alt="Image 2">
        <p style="font-family:cursive;font-size:30px;font-style:italic;">Hibiscus</p></div>
        <div class="gallery-item"><img src="C:\Users\admin\Downloads\Best Flowers for Butterflies.jpeg" alt="Image 3">
        <p style="font-family:cursive;font-size:30px;font-style:italic;">
            Butterfly beauty!
        </p></div>
        <div class="gallery-item"><img src="C:\Users\admin\Downloads\download.jpeg" alt="Image 4">
        <p style="font-family:cursive;font-size:30px;font-style:italic;">Rose</p></div>
        <div class="gallery-item"><img src="C:\Users\admin\Downloads\Spring Has Sprung, Regents Park, London - Claire Justine.jpeg" alt="Image 5">
        <p style="font-family:cursive;font-size:30px;font-style:italic;">Dahlia</p></div>
        <div class="gallery-item"><img src="C:\Users\admin\Downloads\40a02418-653b-4722-8af1-53b88c00c516.jpeg" alt="Image 6">
        <p style="font-family:cursive;font-size:30px;font-style:italic;">Jasmine</p></div>
        <div class="gallery-item"><img src="C:\Users\admin\Downloads\Dahlia Varieties Grouped By Flower Characteristics.jpeg"alt="Image 7">
        <p style="font-family:cursive;font-size:30px;font-style:italic;">Tulip</p></div>
        <div class="gallery-item"><img src="C:\Users\admin\Downloads\Blush Wedding Flowers _ David Austin ‘Queen of Sweden’ Garden Rose.jpeg" alt="Image 8">\
        <p style="font-family:cursive;font-size:30px;font-style:italic;">White rose</p></div>
        <div class="gallery-item"><img src="C:\Users\admin\Downloads\Beautiful Flowers.jpeg"  alt="Image 9">
        <p style="font-family:cursive;font-size:30px;font-style:italic;">Blue pea flower</p></div>
        <div class="gallery-item"><img src="C:\Users\admin\Downloads\IMG_0576.jpeg" alt="Image 10">
        <p style="font-family:cursive;font-size:30px;font-style:italic;">Lotus
        </p></div>
        <div class="gallery-item"><img src="C:\Users\admin\Downloads\Photo by Hiếu Hoàng on Pexels.jpeg" alt="Image 11">
        <p style="font-family:cursive;font-size:30px;font-style:italic;">Gulmohar flower</p></div>
        <div class="gallery-item"><img src="C:\Users\admin\Downloads\36b08d40-4c5d-4112-b91f-cd2998351dd6.jpeg"alt="Image 12">
        <p style="font-family:cursive;font-size:30px;font-style:italic;">paper flower</p></div>
    </div>
</body>
</html>
```
### image.css:

```
<head>
    <style>
h1{
    font-family: "Satisfy", cursive;
    font-size: 85px;
    text-align: center;
    margin-top: 0%;
    color:black
}

body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    margin: 0;
    background-color: #f0f0f0;
}

.gallery {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
    max-width: 1200px;
    margin: 20px;
}
.gallery-item {
    overflow: hidden;
    border-radius: 8px;
}

.gallery-item img {
    width: 100%;
    height: auto;
    display: block;
    transition: transform 0.3s ease;
}

.gallery-item:hover img {
    transform: scale(1.1);
}

</style>
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/ee17d2ca-7102-46a3-96f0-ecc2303590d3)

![image](https://github.com/user-attachments/assets/59bc2994-d137-4693-81d4-852993a66a10)

![image](https://github.com/user-attachments/assets/19d7a972-18e4-4e31-b868-9bfba498d3a6)




## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
