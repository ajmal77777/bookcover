# Ex.05 Book Front Cover Page Design
## Date:

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

## 
PROGRAM:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Fundamentals of Web Application Development - Book Cover</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="book-cover">

    <!-- Sky background clouds (decorative) -->
    <div class="cloud cloud-1"></div>
    <div class="cloud cloud-2"></div>
    <div class="cloud cloud-3"></div>

    <!-- Main content card -->
    <div class="content-card">

      <h1 class="section-title">About the Book</h1>
      <hr class="divider" />

      <p class="book-description">
        This book <span class="highlight">"Fundamentals of Web Application Development"</span>
        provides an engaging journey through the art and science of web design. It explores how
        creativity meets technology to craft visually appealing and user-friendly websites. Readers
        will learn essential design principles, layout techniques, responsive practices, and the
        importance of user experience that transforms ideas into digital reality.
      </p>

      <!-- Quote block -->
      <blockquote class="quote-block">
        <p class="quote-text">
          <em>"Design is not just what it looks like and feels like — design is how it works on the web."</em>
        </p>
      </blockquote>

      <!-- Author card -->
      <div class="author-card">
        <div class="author-photo">
          <img src="author-photo.jpg" alt="H. MOHAMED AJMAL" />
        </div>
        <div class="author-info">
          <h3 class="author-name">H. MOHAMED AJMAL</h3>
          <p class="author-bio">
            H. MOHAMED AJMAL is a renowned educator and writer with several years of experience
            inspiring students and professionals in the field of web development and design.
          </p>
        </div>
      </div>

    </div><!-- /.content-card -->

    <!-- Footer bar -->
    <div class="footer-bar">
      <div class="publisher-info">
        <span class="publisher-name">SEC Publishers</span>
        <span class="publisher-sub">Printed in India</span>
      </div>
      <div class="price-info">
        Price: <span class="price">&#8377;399</span>
      </div>
    </div>

  </div><!-- /.book-cover -->
</body>
</html>


~~~

## OUTPUT:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/be2601c7-6fad-446d-9ab1-79eb072f8d54" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
