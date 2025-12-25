# Ex.08 Design of Interactive Image Gallery
## Date:21-12-2025

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
html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Image Gallery</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(90deg, #8e2de2, #ff6a88, #ffc3a0);
        }

        h1 {
            text-align: center;
            padding: 20px;
            color: white;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            padding: 20px;
            justify-content:center;
        }

        .gallery img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 12px;
            cursor: pointer;
            transition: transform 0.4s, box-shadow 0.4s;
        }

        .gallery img:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 20px rgba(0,0,0,0.4);
        }

    
    </style>
</head>

<body>

    <h1>Foodie Gallery</h1>

    <div class="gallery">
        <img src="https://png.pngtree.com/background/20230413/original/pngtree-food-burger-delicious-tempting-background-picture-image_2423373.jpg" alt="Image 1">
        <img src="https://w0.peakpx.com/wallpaper/117/274/HD-wallpaper-pizza-slice-milted-food-cheese.jpg" alt="Image 2">
        <img src="https://tse4.mm.bing.net/th/id/OIP.JnMF30lk9598qebi2zfyEwHaEK?rs=1&pid=ImgDetMain&o=7&rm=3" alt="Image 3">
        <img src="https://tse2.mm.bing.net/th/id/OIP.Q_pKszl-R7ozyJjPAdM1bQHaEo?rs=1&pid=ImgDetMain&o=7&rm=3" alt="Image 4">
        
    </div>

    
</body>
</html>
```

## OUTPUT:
<img width="1850" height="906" alt="image" src="https://github.com/user-attachments/assets/4ccf7630-d6f3-4744-bdf1-1f9a06bec395" />


## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
