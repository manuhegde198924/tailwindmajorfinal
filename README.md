# tailwindmajorfinal

hosted link of my project:https://manuhegde198924.github.io/tailwindmajorfinal/


WHEN WHERE AND WHAT OF TAILWIND:

Introduction - Tailwind CSS

Tailwind CSS is a Utility first framework that helps us in styling the HTML pages without leaving the HTML file.
This means you can simply add some utility classes in your HTML tags to design your pages swiftly.
Tailwind CSS is an extraordinary framework that will completely change the way you write CSS in your programs.
One major reason for the popularity of Tailwind CSS is its feasible workflow, as it eliminates the need of mapping the CSS to your HTML file.
Nowadays, Tailwind CSS is evolving at a very fast pace. Let’s begin setting up Tailwind CSS-
Installation

First of all, we will install some important programs which will be required throughout our Tailwind Journey-

●        Install VS code: You can easily download the VS code by clicking here. Moreover, Install the live server extension in VS code as it allows us to visualize our static page by opening the page with a live server.

●        Adding Tailwind CSS: To add tailwind CSS to your file, simply visit the official documentation by clicking here. After that, From the play CDN section, just copy the script and add it to the “<head>” of your HTML file. Hence, we can now use Tailwind CSS in our HTML file.

●        Install Node Js: You can Download Nodejs by clicking here. Select your OS and click on next, and your Nodejs will be installed.

●        Installing ‘Tailwind CSS IntelliSense’ extension: This extension provides some advanced features such as autocomplete, syntax highlighting, and linting.

INITAIL STEPS:
npm install -D tailwindcss
Configure Tailwind CSS

After the installation, configure Tailwind CSS by running the given command in the VS Code terminal:

npx tailwindcss init

The above command creates a config file after configuring Tailwind CSS.

Open the “tailwind.config.js” file and provide the name of the HTML file “index.html” as the value for “content”:
 Create a CSS file

The next step is to create a CSS file named “style.css” and type the given command in this file.
@tailwind base;
@tailwind components;
@tailwind utilities;
AND SAVE
Build the CSS file

Let’s now build the Tailwind CSS file with the name “tailwindstyle.css” by utilizing the command given below:
npx tailwindcss -i ./style.css -o ./tailwindstyle.css --watch

In the above command, “-i” specifies the input, and “-o” specifies the output file to save the compiled CSS. Whereas the “–watch” 
flag tells the Tailwind CSS to watch for changes in the input file and recompile the output file automatically on the occurrence of any changes.

NEXT STEP
<link href="./tailwindstyle.css" rel="stylesheet">

FOR STEP BY STEP EXPLAINATION OF MY PROJECT AND SCREENSHOTS U MAY REFER::::----->https://github.com/manuhegde198924/tailwindmajorfinal/issues/1




