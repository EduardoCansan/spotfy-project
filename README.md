
### INITIALIZING THE PROJETCT

1. Insatall the vite:
    - in terminal 
    - npm create vite@latest .  
    - y  
    - chose the technologies of your preference 

2. Install all the packages 
    - in terminal
    - npm i

3. Run the vite:
    - in terminal
    - npm run dev

##

### CURIOSITIES

1. The package.json store all the configs of your project

2. npm install, install all the dependences for the project

3. When it runs the npm run, you're getting from the 
   packag.json files. so you can use npm run ...
   wherever part of the code you want

4. .jsx is like javaScript, but with more sintax, that is
    similar to html

5. All Component in React is a function

6. A void tag in React is called Fragment

7. SVH is a 'Small Viewport Height' this mean the height is
   gone be a 100% of the screen in a small object view, this
   make the responsivity more clear for mobiles and web

8. .single-item:hover .single-item__icon: 
   - i'm using a specific line of code to explain an interesting
     shortcut, so if you use this sintex, the div above it will 
     affect/active the div bellow, is a good method to turn the
     website more interactive and more flashy for the user. 
     As example pass the mouse in the image and the text do a 
     transition, otherwise the text only would do that if you
     pass the mouse in the text, but here you're forcing the
     img to do that when you use other div.

##

### PATTERN CODES

1. Arrow Function (most commom used):
    - const 'Name' = () <></>;

2. Self Closing Tag
    - <'Name'></'Name'> or <'Name' />
    
3. Export in React:
    - default: can be imported with any name and without curly brackets
    - without default: must import with the same name and curly brackets

4. In Css is an excelent patter to do a reset in your elements, in
   the beggining of the 'index.css' is an exemple

5. Name of classes in CSS, metodologia BEM
    - Block = header
    - Elements = header __link
    - Modifiers = header __link--small