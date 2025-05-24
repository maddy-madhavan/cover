# Ex.06 Book Front Cover Page Design
## Date:14/05/2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Wings of Fire - Book Template</title>
  <style>
    body {
      background: #f2e9e4;
      font-family: 'Georgia', serif;
      margin: 0;
      padding: 0;
    }
    .book {
      width: 12cm;          /* typical book width */
      height: 18cm;         /* fixed height */
      margin: 50px auto;
      padding: 20px;
      background: #ffffff;
      box-shadow: 0 10px 30px rgba(0,0,0,0.2);
      border: 2px solid #dcdcdc;
      overflow: hidden;     /* ensure content fits */
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .cover {
      text-align: center;
    }
    .cover img {
      width: 7cm;
      margin-bottom: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.3);
    }
    .title {
      font-size: 24px;
      font-weight: bold;
      margin-bottom: 5px;
    }
    .author {
      font-size: 18px;
      color: #555;
      margin-bottom: 15px;
    }
    .description {
      font-size: 14px;
      line-height: 1.4;
      color: #333;
      text-align: justify;
    }
  </style>
</head>
<body>
<div class="book">
  <div class="cover">
    <img src="abdul.jpeg" alt="Wings of Fire Book Cover">
    
    <div class="title">Wings of Fire</div>
    <div class="author">By Dr. A.P.J. Abdul Kalam</div>
  </div>
  <div class="description">
    "Wings of Fire" is the inspiring autobiography of Dr. A.P.J. Abdul Kalam, who rose from humble beginnings to become India's 11th President and a celebrated scientist. 
    It chronicles his early life, struggles, achievements in the Indian Space Research and Defense sectors, and his vision for India’s future.
  </div>
</div>

</body>
</html>


```

## OUTPUT:
![image](https://github.com/user-attachments/assets/7508456d-6eee-4998-9a7d-207cd3ac8cdb)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
