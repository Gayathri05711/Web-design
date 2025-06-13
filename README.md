A simple personal info web page using HTML and CSS can be created by structuring the content in an HTML file and styling it with CSS, allowing for basic presentation of information like name, profession, contact details, and a short bio. For example, a simple profile card with image and content sections can be designed. 
Here's a breakdown of the process:
1. HTML Structure (index.html):
Code
<!DOCTYPE html>
<html>
<head>
<title>Personal Info</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="container">
  <img src="your-image.jpg" alt="Your Image" class="profile-image">
 <div class="info">
    <h1>Your Name</h1>
    <p class="profession">Profession: Software Engineer</p>
    <p>Location: Sholinganallur, Chennai</p>
    <p>Email: your.email@example.com</p>
    <p>A brief description of yourself goes here.</p>
     <!-- Add social media links if desired -->
  </div>
</div>
</body>
</html>
2. CSS Styling (style.css):
Code
.container {
  display: flex;
  align-items: center;
  text-align: center; /* Center text */
  width: 80%;
  margin: 50px auto; /* Center the container */
  border: 1px solid #ccc;
  padding: 20px;
  border-radius: 8px;
}

.profile-image {
  width: 200px; /* Adjust as needed */
  height: 200px; /* Adjust as needed */
  border-radius: 50%; /* Make it circular */
  object-fit: cover; /* Maintain aspect ratio */
  margin-right: 20px;
}

.info {
  flex: 1;
}

.profession {
  font-style: italic;
}

h1 {
  margin-bottom: 0.5em;
}

p {
  line-height: 1.5;
}
Explanation:
HTML:
The container div uses display: flex to arrange the image and information side-by-side.
The profile-image tag displays your image.
The info div contains your name, profession, location, email, and a brief description.
CSS:
The container class is used to style the overall layout, centering it and adding some basic visual appeal.
The profile-image class is used to style the image, making it circular and setting its size.
The profession class is used to style the profession text as italic. 
Key points to remember:
Image: Replace "your-image.jpg" with the actual path to your image file.
Personal Information: Update the text within the info div with your own details.
CSS Customization: Adjust the CSS styles (fonts, colors, sizes, etc.) to match your desired look and feel.
File Paths: Ensure your CSS file (style.css) is linked correctly in the HTML. 
This basic structure provides a foundation for a personal info page. You can further expand it by adding more sections, different layouts, or even interactive elements. 
Building Your First Web Page - Learn to Code HTML & CSS
HTML, HyperText Markup Language, gives content structure and meaning by defining that content. 
How to Create a Website using HTML and CSS
Step 1: Create a Layout.
Step 2: Set up the boiler code.
    Basic Structure:
Code
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>
  </body>
</html>1. Basic Structure:
Code

<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>
  </body>
</html>




