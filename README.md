q1.# WEB-Development-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Basics</title>
</head>
<body>
    <h1>HTML defines the content and structure of your website</h1>
</body>
</html>
q2.Comments in HTML are used to add notes or explanations within the code that are ignored by the browser when rendering the page. They help developers understand the code, document changes, and temporarily disable parts of the code without deleting them.

Key Uses of HTML Comments:
Code Explanation: Helps other developers understand the purpose of specific code sections.
Debugging: Allows you to temporarily disable certain lines of code.
Future Reference: Notes for yourself when revisiting the code later.
Example of Comments in HTML
html
Copy
Edit
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Comments Example</title>
</head>
<body>
    <!-- This is a main heading -->
    <h1>Welcome to My Website</h1>

    <!-- This paragraph gives an introduction -->
    <p>This website is designed to showcase HTML examples.</p>

    <!-- The following section is temporarily removed -->
    <!-- 
    <h2>Coming Soon</h2>
    <p>New features will be added soon. Stay tuned!</p> 
    -->

    <!-- End of document -->
</body>
</html>
question3.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Web Page Layout</title>
</head>
<body>
    <h1>Welcome to My Web Page</h1>
    
    <hr> <!-- Horizontal line to separate sections -->
    
    <p>This is a paragraph of text that provides some information about the web page. 
       HTML is a markup language used to structure content on the web.</p>
    
    <br> <!-- Line break to add extra space -->

    <p>Here is another paragraph after a line break. You can use different HTML tags 
       to create structured and well-formatted web pages.</p>
</body>
</html>
---->>>>q4.1. Tag:
A tag is a keyword enclosed in angle brackets (<>) that defines an HTML structure. It tells the browser how to format content. Tags usually come in pairs (opening and closing), but some are self-closing.

Example of a Tag:
html
Copy
Edit
<p>This is a paragraph.</p>
<p> is the opening tag.
</p> is the closing tag.
Everything between them is the content.
2. Element:
An element consists of an opening tag, content, and a closing tag. Some elements are empty (self-closing), like <br> or <img>.

Example of an Element:
html
Copy
Edit
<h1>Welcome to My Website</h1>
<h1> is the opening tag.
"Welcome to My Website" is the content.
</h1> is the closing tag.
Together, they form an HTML element.
Example of a Self-Closing Element:
html
Copy
Edit
<img src="image.jpg" alt="A sample image">
<img> is an empty element (no closing tag).

q5.The <!DOCTYPE> declaration is used to specify the document type and version of HTML being used. It helps the web browser render the page correctly by following the appropriate HTML standards.




