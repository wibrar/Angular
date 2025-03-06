# Angular
Learning Angular and Typescript.


- What is Angular 
Is two things
1. Front end java framework.
2. Collection of tools we can use for web development

- Why use ANgular?
Why a framework?
Frameworks like angular do really shine. Simpolifies building complex, interactive web user interfaces.
To write a declarative code. Dont have to manually reach out to DOM elements.
You define the target state or states.
Have components which are custome HTML elements.

Reduce the complexity of the web app.
Angular uses Typescript. not vanilla Javascript.


- it keeps on evolving. Every 6 months.
new releases doesnot break your code.
Updates in  a backwared copatoble way.


- Creating an angular project.
What is  an Angular CLI?
Simplifies the process of creating angular projects.
Dvee;opm,emt testing server.
You need to install it to use Anguolar.

I created my first angular project.
Did basic Node.js set up and npm.


- Module Introducton
Learn how angular projects are structured. Wroking with ath e components
How to handle user events
How to  write angular code to make a dynamic web app.

- Open the first project and learn the files.
.json, how the typescript code will be compiled to javascript

Initially the file had errors in main.ts file. I had to install node Packages by opening terminal. `npm install`.

- scripts are injected in the HTML by the angular CLI. 
Learned how components end up on the screen.

-slpit elements by multiple components.
build building blocks as individualcomponents.
how to name components.
name.component.ts
name the class like NameComponent

- String interpolation nd property binding
-binding attributes
- Learnt users event listener.
- How to change the state and manage data.
- learnt that angular has a property that it checks what data has been changed and easily, withour any extra work adds changes to the HTML.
angular has its own framework zone.js
automatically listens to aall user events
its checks the angular application for any changes

- what are signals?
another way to store the sate of a variable
donot have a initial value, it can be changesd, use a set method to change the value
when using signals you have to put the value in the html as a function not a variable. by using () parenthesis
it tells angular that you a re trying to get that value as a signal. and rhis value will be reevaluated, sets upa a tracking mechanism
Zonen instead is a grouping mechanism that checks all kinds of changes in the angular app, could be data change. 
Signals makes angular get rid of Zone concept.

- how does angular have flexible components.
- changed the whole structure of the app. 
used components input decorater
! with any Input variable means it currently is nopt initialised but it will be later in the app.
the app component now has a the users imported and are accessed there. 