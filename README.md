# coding-platform
# codeDive-
PROJECT NAME:

CodeDive - Competitive Programming Practice Platform
Dive into the world of competitive programming and master data structures with CodeDive

INTRODUCTION:

CodeDive is a dynamic online platform designed for the sharpening of an enthusiastic coder’s problem solving abilities. An extensive set of problems are provided in the website with the option to practice them in the user’s preferred language. The difficulty of the problems ranges from easy to hard to so this website can be used by experts and beginners alike. Whether you’re a student, a professional developer or someone simply passionate about coding, CodeDive offers a platform where you can learn.
FRONTEND:

For the frontend part, we did the following:
●	User Interface Design: The design of the User Interface (UI) of the website was a function of the frontend. This involves the creation of the layout, navigation and visual elements of the site. 
●	HTML/CSS: The visual design and elements of the website was done using HTML and the styling of these elements was done by CSS.
●	JavaScript: JavaScript was used to add interactivity to the website. It has been used in places like the Login, Sign up, Practice problems etc.

BACKEND:

●	For the Login and Sign up pages, we used backend frameworks(Node.js, Express.js) to get the information about the user.
  

●	This information is then stored in the database with the help of MongoDB. If the login details are incorrect, the user gets directed to invalid credentials page.
 
 
●	We also had to embed an online text editor into our website so that it can act as a text editor for various languages. 

EMBEDDING THE EDITOR:

1.	Integration: We incorporated the CodeMirror library into our web application framework. This involved using the necessary HTML and CSS files and initializing the CodeMirror instance within our code editor component.
2.	Customization: We configured syntax highlighting, autocomplete and some other features to enhance the coding experience for the users.
3.	Error highlighting: One of the notable features we implemented using CodeMirror wad error-highlighting. By leveraging CodeMirror’s API, we were able to dynamically mark syntax errors and display messages to users and aid in the debugging process.

SHORTCOMINGS:

The idea was for CodeMirror to seamlessly integrate with the compiler pipeline. But there were certain things that didn’t satisfy our overall requirement of what we needed from the editor. For example, it only allowed the compilation process in JavaScript. Second, the CodeMirror files didn’t contain any option on how to accept user input and print the output. Due to these reasons, we had to link an online compiler into our site instead.

CONCLUSION:

The idea was to create a competitive programming website. For the most part, it works fine but for it to have been fully functional, we need to overcome some challenges like creating a separate compiler for C, Python and C++. We also need a separate login system for professor so that he/she can add problems and add info to the DSA topics.
